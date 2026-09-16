# LLMjacking, caught by a planted canary

*A short field note from the Trapline sensor network. TLP:CLEAR — share freely.*

We run a handful of decoy AI servers: ordinary-looking boxes exposing the APIs of popular
model-serving stacks (Ollama, vLLM, llama.cpp) and notebook/compute tools (Jupyter, Ray).
They serve nothing real. Some of them leak a fake `.env` file when a scanner asks for one,
and that file contains two tripwire credentials nobody legitimate would ever hold: a cloud
key and a model-API key. Touch either and it reports home. This note is what happened when
someone did.

## The chain

The interesting part of credential theft against AI boxes is that it happens in two moves,
usually from two different machines. One host harvests the `.env`; a *different* host tests
the stolen key later, so the machine that commits the abuse never appears in the victim's
logs. We saw exactly that, end to end, because the tripwire fires wherever the key is used.

| When (UTC) | What happened | Source IP |
|---|---|---|
| 2026-09-15 11:35 | Fetched the fake `.env` from a decoy AI box | `45.153.34.54` |
| 2026-09-15 11:41 | Used the planted cloud key against the real cloud (`ListBuckets`), ~6 min later | `217.60.241.51` |
| 2026-09-16 08:55 | Same key reused: `ListBuckets` again | `217.60.241.51` |
| 2026-09-16 08:59 | Escalated to `ListObjects` — trying to read bucket contents | `217.60.241.51` |

The harvest host and the abuse host are different by design. The abuse host never brute-
forced anything, never scanned a port we watch — the only reason we know it exists is that
it used a key that could only have come from our decoy. It came back the next day and tried
again, moving from "does this key work" to "what can I take with it." The key is a tripwire
with no permissions, so every call is denied, but each attempt still reports the caller.

An earlier harvest wave pulled the same file from cloud hosts in Singapore
(`161.118.213.33`, `161.118.244.13`), enumerating every common `.env` variant
(`.env`, `.env.local`, `.env.production`, `.env.bak`) before probing the model endpoints —
the signature of automated tooling that scrapes config files at scale.

## They also drive the models

Credential theft isn't the only AI-aware behavior. One host (`54.37.84.93`) ran a textbook
**model-capability enumeration** sweep against a decoy: a burst of one-line chat requests,
each naming a different brand-name model (`gpt-5.5`, `deepseek-v4-pro`, `claude-fable-5.1`,
`kimi-k3`, and more), with tiny token limits and throwaway prompts like `Reply OK`. That is
not someone trying to get work done — it is someone cataloging which models a free or
stolen endpoint will serve, the reconnaissance that precedes reselling stolen inference.

## What this means for defenders

- **Assume any `.env` on an internet-facing AI service is harvested within minutes.** The
  scrape-to-abuse gap here was under six minutes, and fully automated.
- **A real leaked cloud key on such a box is compromised, not "at risk."** Rotate on
  discovery; don't wait.
- **The abuse comes from infrastructure your honeypots can't see.** A tripwire credential
  is the only thing that surfaces the host that actually uses a stolen key.
- **AI endpoints are now a target in their own right**, not just another open port —
  model enumeration and config-harvesting are distinct, growing behaviors.

## Indicators

All of these are in the feed. The credential-abuse host is confidence 98 — it used a key
nobody legitimate holds.

| IP | Role |
|---|---|
| `217.60.241.51` | Used the planted cloud key (LLMjacking); repeat + escalation |
| `45.153.34.54` | Harvested the canary `.env` ~6 min before first key use |
| `161.118.213.33`, `161.118.244.13` | Earlier `.env` harvest wave, full variant sweep |
| `54.37.84.93` | Model-capability enumeration against a decoy |

Machine-readable: [`feeds/llmjacking.txt`](../feeds/llmjacking.txt) and
[`feeds/ai-infra.txt`](../feeds/ai-infra.txt).
