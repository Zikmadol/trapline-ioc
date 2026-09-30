# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1261 attackers** · **284,150 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 78 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 85 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 528 |
| `ssh-bruteforce` | 299 |
| `redis-exploit` | 248 |
| `mcp-abuse` | 80 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 17 |
| `docker-abuse` | 13 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 848 |
| `redis` | 256 |
| `mcp` | 114 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 38 |
| `hfhub` | 35 |
| `litellm` | 35 |
| `docker` | 28 |
| `ollama` | 18 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 496 |
| `345gs5662d34` | 425 |
| `admin` | 255 |
| `ubuntu` | 102 |
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
| `3245gs5662d34` | 426 |
| `345gs5662d34` | 425 |
| `123456` | 249 |
| `123` | 139 |
| `1234` | 122 |
| `admin` | 80 |
| `12345678` | 75 |
| `000000` | 66 |
| `password` | 65 |
| `12345` | 60 |
| `1` | 58 |
| `!QAZ2wsx` | 55 |
| `0` | 53 |
| `0000` | 52 |
| `!Q2w3e4r` | 51 |

### Top commands run

| command | times |
|---|---|
| `uname` | 546 |
| `echo` | 488 |
| `lscpu` | 478 |
| `crontab` | 475 |
| `cd` | 473 |
| `cat` | 472 |
| `top` | 439 |
| `ls` | 438 |
| `df` | 438 |
| `free` | 438 |
| `whoami` | 437 |
| `w` | 436 |
| `INFO` | 165 |
| `canary_env` | 100 |
| `PING` | 99 |


_Generated from first-party honeypot capture. CC BY 4.0._
