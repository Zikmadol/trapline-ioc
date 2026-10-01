# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1369 attackers** · **308,422 hostile actions** · covering 19 day(s) through 2026-10-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 92 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 95 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 580 |
| `ssh-bruteforce` | 327 |
| `redis-exploit` | 263 |
| `mcp-abuse` | 87 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 21 |
| `docker-abuse` | 14 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 930 |
| `redis` | 271 |
| `mcp` | 124 |
| `llamacpp` | 76 |
| `vllm` | 48 |
| `jupyter` | 42 |
| `litellm` | 41 |
| `hfhub` | 36 |
| `docker` | 29 |
| `ollama` | 19 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 551 |
| `345gs5662d34` | 464 |
| `admin` | 285 |
| `ubuntu` | 127 |
| `administrator` | 89 |
| `admin1` | 67 |
| `user` | 61 |
| `admin2` | 58 |
| `adminuser` | 58 |
| `test` | 57 |
| `a` | 57 |
| `ai` | 57 |
| `AdminGPON` | 55 |
| `aaa` | 55 |
| `admin123` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 467 |
| `345gs5662d34` | 464 |
| `123456` | 291 |
| `123` | 172 |
| `1234` | 156 |
| `admin` | 87 |
| `12345678` | 87 |
| `password` | 73 |
| `1` | 71 |
| `000000` | 71 |
| `12345` | 71 |
| `!QAZ2wsx` | 61 |
| `0` | 59 |
| `123456789` | 57 |
| `0000` | 56 |

### Top commands run

| command | times |
|---|---|
| `uname` | 604 |
| `echo` | 538 |
| `lscpu` | 526 |
| `crontab` | 525 |
| `cd` | 517 |
| `cat` | 516 |
| `top` | 479 |
| `ls` | 478 |
| `df` | 478 |
| `free` | 478 |
| `whoami` | 477 |
| `w` | 476 |
| `INFO` | 174 |
| `canary_env` | 108 |
| `PING` | 106 |


_Generated from first-party honeypot capture. CC BY 4.0._
