# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1279 attackers** · **285,469 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 79 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 88 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 542 |
| `ssh-bruteforce` | 301 |
| `redis-exploit` | 250 |
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
| `ssh` | 864 |
| `redis` | 258 |
| `mcp` | 115 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 39 |
| `hfhub` | 35 |
| `litellm` | 35 |
| `docker` | 28 |
| `ollama` | 19 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 509 |
| `345gs5662d34` | 437 |
| `admin` | 260 |
| `ubuntu` | 108 |
| `administrator` | 78 |
| `admin1` | 64 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `user` | 51 |
| `admin123` | 49 |
| `Asalem` | 48 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 439 |
| `345gs5662d34` | 437 |
| `123456` | 257 |
| `123` | 144 |
| `1234` | 128 |
| `admin` | 81 |
| `12345678` | 79 |
| `password` | 67 |
| `000000` | 67 |
| `12345` | 61 |
| `1` | 60 |
| `!QAZ2wsx` | 55 |
| `0` | 53 |
| `0000` | 52 |
| `!Q2w3e4r` | 51 |

### Top commands run

| command | times |
|---|---|
| `uname` | 560 |
| `echo` | 501 |
| `lscpu` | 491 |
| `crontab` | 488 |
| `cd` | 486 |
| `cat` | 485 |
| `top` | 452 |
| `ls` | 451 |
| `df` | 451 |
| `free` | 451 |
| `whoami` | 450 |
| `w` | 449 |
| `INFO` | 166 |
| `canary_env` | 100 |
| `PING` | 100 |


_Generated from first-party honeypot capture. CC BY 4.0._
