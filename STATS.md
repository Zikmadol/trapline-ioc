# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1248 attackers** · **281,645 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 78 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 81 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 519 |
| `ssh-bruteforce` | 300 |
| `redis-exploit` | 247 |
| `mcp-abuse` | 78 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 16 |
| `docker-abuse` | 13 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 839 |
| `redis` | 255 |
| `mcp` | 112 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 38 |
| `hfhub` | 35 |
| `litellm` | 33 |
| `docker` | 28 |
| `ollama` | 18 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 487 |
| `345gs5662d34` | 416 |
| `admin` | 251 |
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
| `3245gs5662d34` | 417 |
| `345gs5662d34` | 416 |
| `123456` | 239 |
| `123` | 137 |
| `1234` | 120 |
| `admin` | 79 |
| `12345678` | 73 |
| `000000` | 66 |
| `password` | 62 |
| `12345` | 60 |
| `1` | 59 |
| `!QAZ2wsx` | 55 |
| `0` | 53 |
| `0000` | 52 |
| `!Q2w3e4r` | 51 |

### Top commands run

| command | times |
|---|---|
| `uname` | 537 |
| `echo` | 479 |
| `lscpu` | 469 |
| `crontab` | 466 |
| `cd` | 464 |
| `cat` | 463 |
| `top` | 430 |
| `ls` | 429 |
| `df` | 429 |
| `free` | 429 |
| `whoami` | 428 |
| `w` | 427 |
| `INFO` | 165 |
| `PING` | 99 |
| `canary_env` | 97 |


_Generated from first-party honeypot capture. CC BY 4.0._
