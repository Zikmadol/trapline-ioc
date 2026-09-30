# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1250 attackers** · **283,240 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 78 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 81 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 522 |
| `ssh-bruteforce` | 298 |
| `redis-exploit` | 247 |
| `mcp-abuse` | 78 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 16 |
| `docker-abuse` | 13 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 840 |
| `redis` | 255 |
| `mcp` | 112 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 38 |
| `hfhub` | 35 |
| `litellm` | 34 |
| `docker` | 28 |
| `ollama` | 18 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 489 |
| `345gs5662d34` | 419 |
| `admin` | 252 |
| `ubuntu` | 98 |
| `administrator` | 78 |
| `admin1` | 64 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 51 |
| `admin123` | 49 |
| `Asalem` | 48 |
| `Caps` | 48 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 420 |
| `345gs5662d34` | 419 |
| `123456` | 243 |
| `123` | 139 |
| `1234` | 120 |
| `admin` | 79 |
| `12345678` | 73 |
| `000000` | 66 |
| `password` | 62 |
| `12345` | 60 |
| `1` | 58 |
| `!QAZ2wsx` | 55 |
| `0` | 53 |
| `0000` | 52 |
| `!Q2w3e4r` | 51 |

### Top commands run

| command | times |
|---|---|
| `uname` | 540 |
| `echo` | 482 |
| `lscpu` | 472 |
| `crontab` | 469 |
| `cd` | 467 |
| `cat` | 466 |
| `top` | 433 |
| `ls` | 432 |
| `df` | 432 |
| `free` | 432 |
| `whoami` | 431 |
| `w` | 430 |
| `INFO` | 165 |
| `PING` | 99 |
| `canary_env` | 98 |


_Generated from first-party honeypot capture. CC BY 4.0._
