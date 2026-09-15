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

## `manifest.json`
Build metadata only: `feed`, `generated`, `count`, `confidence_min`, `confidence_max`,
`license`. Poll this to detect updates cheaply.

## Categories

| Category | Meaning |
|---|---|
| `ssh-bruteforce` | Tried credentials against the SSH decoy. |
| `redis-exploit` | Ran exploitation commands against the Redis decoy. |
| `ollama-abuse` / `llamacpp-abuse` / `vllm-abuse` | Drove an exposed-AI decoy's API. |
| `jupyter-*` / `ray-*` | Hit the Jupyter or Ray decoy's execution surface. |
| `canary-aws-key` | Used a planted AWS credential (highest confidence). |
| `payload-host` | A stage-2 host named inside a captured attack payload. |
