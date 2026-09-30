# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1289 attackers** · **286,459 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 81 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 88 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 547 |
| `ssh-bruteforce` | 302 |
| `redis-exploit` | 252 |
| `mcp-abuse` | 80 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 19 |
| `docker-abuse` | 13 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 870 |
| `redis` | 260 |
| `mcp` | 116 |
| `llamacpp` | 72 |
| `vllm` | 44 |
| `jupyter` | 40 |
| `litellm` | 37 |
| `hfhub` | 35 |
| `docker` | 28 |
| `ollama` | 19 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 514 |
| `345gs5662d34` | 439 |
| `admin` | 262 |
| `ubuntu` | 109 |
| `administrator` | 79 |
| `admin1` | 64 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `user` | 53 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `admin123` | 50 |
| `test` | 48 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 441 |
| `345gs5662d34` | 439 |
| `123456` | 261 |
| `123` | 147 |
| `1234` | 131 |
| `admin` | 81 |
| `12345678` | 81 |
| `password` | 68 |
| `000000` | 67 |
| `12345` | 63 |
| `1` | 62 |
| `!QAZ2wsx` | 55 |
| `0` | 54 |
| `0000` | 53 |
| `!Q2w3e4r` | 51 |

### Top commands run

| command | times |
|---|---|
| `uname` | 565 |
| `echo` | 505 |
| `lscpu` | 495 |
| `crontab` | 492 |
| `cd` | 489 |
| `cat` | 488 |
| `top` | 454 |
| `ls` | 453 |
| `df` | 453 |
| `free` | 453 |
| `whoami` | 452 |
| `w` | 451 |
| `INFO` | 167 |
| `PING` | 102 |
| `canary_env` | 100 |


_Generated from first-party honeypot capture. CC BY 4.0._
