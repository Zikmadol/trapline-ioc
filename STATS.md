# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1096 attackers** · **235,522 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 62 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 66 |
| Stage-2 hosts named in payloads | 20 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 437 |
| `ssh-bruteforce` | 261 |
| `redis-exploit` | 225 |
| `mcp-abuse` | 76 |
| `llamacpp-abuse` | 21 |
| `litellm-key-replay` | 15 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 717 |
| `redis` | 233 |
| `mcp` | 107 |
| `llamacpp` | 66 |
| `vllm` | 41 |
| `jupyter` | 37 |
| `hfhub` | 34 |
| `litellm` | 30 |
| `docker` | 22 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 402 |
| `345gs5662d34` | 348 |
| `admin` | 217 |
| `administrator` | 66 |
| `ubuntu` | 62 |
| `admin1` | 51 |
| `AdminGPON` | 44 |
| `aaa` | 44 |
| `a` | 43 |
| `admin2` | 43 |
| `adminuser` | 43 |
| `ai` | 42 |
| `admin123` | 41 |
| `Asalem` | 40 |
| `Caps` | 40 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 348 |
| `345gs5662d34` | 348 |
| `123456` | 193 |
| `123` | 120 |
| `1234` | 99 |
| `admin` | 70 |
| `12345678` | 60 |
| `000000` | 53 |
| `12345` | 47 |
| `!QAZ2wsx` | 47 |
| `1` | 46 |
| `0` | 45 |
| `0000` | 44 |
| `password` | 43 |
| `123456789` | 43 |

### Top commands run

| command | times |
|---|---|
| `uname` | 446 |
| `echo` | 400 |
| `lscpu` | 392 |
| `crontab` | 389 |
| `cd` | 386 |
| `cat` | 386 |
| `top` | 361 |
| `ls` | 360 |
| `df` | 360 |
| `free` | 360 |
| `whoami` | 359 |
| `w` | 358 |
| `INFO` | 152 |
| `canary_env` | 95 |
| `PING` | 88 |


_Generated from first-party honeypot capture. CC BY 4.0._
