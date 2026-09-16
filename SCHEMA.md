# Schema

Several views of the same data, regenerated together and append-only.

## `daily/`
One pair of files per day, named by date (UTC): `daily/YYYY-MM-DD.txt` (plain IP list) and
`daily/YYYY-MM-DD.csv` (same columns as `indicators.csv`). Each holds the IPs **first seen**
that day. Files are append-only: a past day never changes once written, so you can fetch a
date once and cache it. `manifest.json` lists the covered range (`first_day`, `last_day`).

## `ips.txt`
Plain text, one IPv4 per line. Lines starting with `#` are comments (header only). This
is the firewall/blocklist view.

## `indicators.csv`
Header row, then one row per IP:

| Column | Type | Notes |
|---|---|---|
| `ip` | string | IPv4. |
| `category` | string | Primary category, e.g. `ssh-bruteforce`, `redis-exploit`, `ollama-abuse`, `canary-aws-key`, `payload-host`. |
| `confidence` | int | 0–100. 90 = direct decoy observation; 98 = planted-credential use. |
| `first_seen` | date | `YYYY-MM-DD` UTC, or empty. |
| `last_seen` | date | `YYYY-MM-DD` UTC, or empty. |
| `tags` | string | `|`-separated coarse labels. |

## `indicators.json`
```json
{
  "feed": "trapline-ioc",
  "generated": "2026-09-15T19:14:39+00:00",
  "count": 55,
  "license": "CC-BY-4.0",
  "description": "...",
  "indicators": [
    {
      "ip": "217.60.241.51",
      "category": "canary-aws-key",
      "categories": ["canary-aws-key"],
      "confidence": 98,
      "first_seen": "2026-09-15",
      "last_seen": "2026-09-15",
      "tags": ["canary", "cloud-abuse", "credential-abuse", "honeypot"]
    }
  ]
}
```

## `feeds/` — AI-threat sub-feeds
Focused, all-time cumulative views regenerated with every build. Same schema as the
top-level files, filtered to the AI-targeting activity that is this feed's reason to exist.

| File | Membership |
|---|---|
| `feeds/ai-infra.txt` / `.csv` | Attacked AI infrastructure: drove an exposed-AI decoy (Ollama/vLLM/llama.cpp/Jupyter/Ray), ran GPU/AI-hardware recon, or used a credential planted on an AI box. |
| `feeds/gpu-probing.txt` | Ran GPU / AI-hardware reconnaissance (`nvidia-smi`, `lspci \| grep nvidia`). |
| `feeds/llmjacking.txt` / `.csv` | Used a cloud credential planted in an AI server's `.env` — canary-confirmed (confidence 98). |

The `.txt` files are one IP per line with `#` comment headers; the `.csv` files use the
same columns as `indicators.csv`.

## `manifest.json`
Build metadata: `feed`, `generated`, `count`, `days`, `first_day`, `last_day`, `license`,
plus a count for each sub-feed (`ai_infra`, `gpu_probing`, `llmjacking`) and a `subfeeds`
object. Poll this to detect updates cheaply.

## Categories

| Category | Meaning |
|---|---|
| `ssh-bruteforce` | Tried credentials against the SSH decoy. |
| `redis-exploit` | Ran exploitation commands against the Redis decoy. |
| `ollama-abuse` / `llamacpp-abuse` / `vllm-abuse` | Drove an exposed-AI decoy's API. |
| `jupyter-*` / `ray-*` | Hit the Jupyter or Ray decoy's execution surface. |
| `canary-aws-key` | Used a planted AWS credential (highest confidence). |
| `payload-host` | A stage-2 host named inside a captured attack payload. |

Notable tags: **`gpu-probing`** — the source ran GPU / AI-hardware reconnaissance (e.g. `lspci | grep nvidia`, `nvidia-smi`), hunting for AI infrastructure. **`canary`** — used one of our planted canary credentials.
