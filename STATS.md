# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1191 attackers** · **264,452 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 74 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 76 |
| Stage-2 hosts named in payloads | 21 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 489 |
| `ssh-bruteforce` | 288 |
| `redis-exploit` | 237 |
| `mcp-abuse` | 76 |
| `llamacpp-abuse` | 22 |
| `litellm-key-replay` | 17 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 797 |
| `redis` | 245 |
| `mcp` | 108 |
| `llamacpp` | 71 |
| `vllm` | 42 |
| `jupyter` | 38 |
| `hfhub` | 34 |
| `litellm` | 33 |
| `docker` | 24 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 459 |
| `345gs5662d34` | 389 |
| `admin` | 239 |
| `ubuntu` | 82 |
| `administrator` | 75 |
| `admin1` | 58 |
| `a` | 51 |
| `admin2` | 50 |
| `ai` | 50 |
| `AdminGPON` | 49 |
| `aaa` | 49 |
| `adminuser` | 48 |
| `admin123` | 46 |
| `Asalem` | 45 |
| `Caps` | 45 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 389 |
| `345gs5662d34` | 389 |
| `123456` | 221 |
| `123` | 130 |
| `1234` | 106 |
| `admin` | 76 |
| `12345678` | 65 |
| `000000` | 62 |
| `password` | 60 |
| `1` | 57 |
| `12345` | 56 |
| `!QAZ2wsx` | 52 |
| `0` | 50 |
| `0000` | 49 |
| `!Q2w3e4r` | 48 |

### Top commands run

| command | times |
|---|---|
| `uname` | 503 |
| `echo` | 448 |
| `lscpu` | 439 |
| `crontab` | 436 |
| `cat` | 433 |
| `cd` | 432 |
| `top` | 403 |
| `ls` | 402 |
| `df` | 402 |
| `free` | 402 |
| `whoami` | 401 |
| `w` | 400 |
| `INFO` | 160 |
| `canary_env` | 95 |
| `PING` | 94 |


_Generated from first-party honeypot capture. CC BY 4.0._
