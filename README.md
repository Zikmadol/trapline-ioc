# Trapline IOC feed

A small, free feed of **IP addresses caught attacking honeypot sensors**. Every address
here took a hostile action against a decoy that hosts nothing legitimate, so there is no
reason for a real user to touch it. Updated continuously from first-party observation.

No aggregation of other people's lists, no scraped blocklists. These are IPs our own
sensors and canaries confirmed, first-hand.

## Use it

Plain list, one IP per line — drop it straight into a firewall, an allowlist checker, or
a SIEM:

```
curl -s https://raw.githubusercontent.com/Zikmadol/trapline-ioc/main/ips.txt
```

Need context? [`indicators.csv`](indicators.csv) and [`indicators.json`](indicators.json)
carry the category, confidence, and first/last-seen dates for each IP. See
[SCHEMA.md](SCHEMA.md).

Want just what's new? The [`daily/`](daily) folder has one file per day —
`daily/YYYY-MM-DD.txt` and `.csv` — holding the IPs first seen that day. Pull only the
dates you don't have yet:

```
curl -s https://raw.githubusercontent.com/Zikmadol/trapline-ioc/main/daily/$(date -u +%F).txt
```

## What's in it

| Field | Meaning |
|---|---|
| `ip` | The attacker address. |
| `category` | What it did, e.g. `ssh-bruteforce`, `ollama-abuse`, `canary-aws-key`, `payload-host`. |
| `confidence` | 90 = direct observation on our decoys. 98 = used a credential we planted (unambiguous). |
| `first_seen` / `last_seen` | UTC dates we observed it. |
| `tags` | Coarse labels: protocol, `bruteforce`/`exploit`/`abuse`, `key-replay`, `canary`, `cloud-abuse`, `gpu-probing`, `stage2`. |

Confidence is deliberately high because there are no bystanders here. An IP that
brute-forced an SSH decoy, drove a fake AI endpoint, or used a leaked canary key is not a
misconfigured CDN — it chose to attack something with no legitimate purpose.

## How it's collected

The sensors are ordinary-looking servers that exist only to be attacked: an SSH endpoint,
Redis, and a set of exposed-AI decoys (Ollama, llama.cpp, vLLM, Jupyter, Ray). They grant
nothing and run nothing. A few of them leak a fake `.env` with canary credentials; when a
stolen key is used, the IP that used it lands here at the highest confidence.

Deliberately **not** published: the credentials and prompts attackers sent, client
fingerprints, sensor locations, and how the canaries are wired. This feed is the
actionable half — the addresses — nothing that would help an attacker evade the sensors.

## Cadence

Updated hourly from live capture. It's **append-only**: an IP is published once, into the
daily file for the day we first saw it, and never moved or removed — so the per-day
history stands even as old raw logs age out. `manifest.json` carries the `generated`
timestamp, the total count, and the covered date range.

## Accuracy & removals

This is best-effort threat data offered without warranty. If you believe an address is
listed in error — a shared NAT, a security scanner you operate, a rotated cloud IP — open
an issue and it will be reviewed. Attacker IP addresses are processed on the basis of the
legitimate interest in network security; only addresses that took a hostile action are
included, and known-benign infrastructure (public resolvers, our own hosts) is filtered.

## License

[Creative Commons Attribution 4.0](LICENSE) (CC BY 4.0). Use it for anything — commercial
or not — just credit "Trapline IOC feed" with a link back.
