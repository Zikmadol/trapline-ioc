# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**914 attackers** · **181,808 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 48 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 33 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 357 |
| `ssh-bruteforce` | 231 |
| `redis-exploit` | 194 |
| `mcp-abuse` | 64 |
| `llamacpp-abuse` | 19 |
| `ollama-abuse` | 9 |
| `docker-abuse` | 9 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 604 |
| `redis` | 200 |
| `mcp` | 86 |
| `llamacpp` | 57 |
| `vllm` | 31 |
| `jupyter` | 27 |
| `hfhub` | 21 |
| `docker` | 18 |
| `ollama` | 11 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 331 |
| `345gs5662d34` | 284 |
| `admin` | 181 |
| `administrator` | 55 |
| `ubuntu` | 49 |
| `admin1` | 42 |
| `aaa` | 36 |
| `admin2` | 35 |
| `AdminGPON` | 34 |
| `a` | 34 |
| `adminuser` | 34 |
| `ai` | 34 |
| `Asalem` | 32 |
| `admin123` | 32 |
| `Caps` | 31 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 284 |
| `3245gs5662d34` | 283 |
| `123456` | 161 |
| `123` | 100 |
| `1234` | 81 |
| `admin` | 62 |
| `12345678` | 47 |
| `000000` | 44 |
| `12345` | 41 |
| `123456789` | 40 |
| `password` | 38 |
| `!QAZ2wsx` | 38 |
| `1` | 37 |
| `0000` | 37 |
| `0` | 35 |

### Top commands run

| command | times |
|---|---|
| `uname` | 365 |
| `echo` | 326 |
| `lscpu` | 318 |
| `cat` | 317 |
| `cd` | 316 |
| `crontab` | 315 |
| `top` | 294 |
| `ls` | 293 |
| `df` | 293 |
| `free` | 293 |
| `whoami` | 292 |
| `w` | 291 |
| `INFO` | 133 |
| `canary_env` | 80 |
| `PING` | 69 |


_Generated from first-party honeypot capture. CC BY 4.0._
