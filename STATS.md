# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1382 attackers** · **317,237 hostile actions** · covering 19 day(s) through 2026-10-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 94 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 96 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 586 |
| `ssh-bruteforce` | 328 |
| `redis-exploit` | 266 |
| `mcp-abuse` | 87 |
| `llamacpp-abuse` | 24 |
| `litellm-key-replay` | 21 |
| `docker-abuse` | 15 |
| `ollama-abuse` | 12 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 938 |
| `redis` | 274 |
| `mcp` | 124 |
| `llamacpp` | 77 |
| `vllm` | 48 |
| `jupyter` | 42 |
| `litellm` | 41 |
| `hfhub` | 37 |
| `docker` | 30 |
| `ollama` | 20 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 554 |
| `345gs5662d34` | 467 |
| `admin` | 288 |
| `ubuntu` | 131 |
| `administrator` | 89 |
| `admin1` | 67 |
| `user` | 63 |
| `test` | 58 |
| `admin2` | 58 |
| `adminuser` | 58 |
| `a` | 57 |
| `ai` | 57 |
| `AdminGPON` | 55 |
| `aaa` | 55 |
| `admin123` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 470 |
| `345gs5662d34` | 467 |
| `123456` | 294 |
| `123` | 176 |
| `1234` | 156 |
| `12345678` | 89 |
| `admin` | 87 |
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
| `uname` | 611 |
| `echo` | 542 |
| `lscpu` | 529 |
| `crontab` | 528 |
| `cd` | 523 |
| `cat` | 523 |
| `ls` | 482 |
| `top` | 482 |
| `df` | 481 |
| `free` | 481 |
| `whoami` | 480 |
| `w` | 479 |
| `INFO` | 176 |
| `canary_env` | 109 |
| `PING` | 109 |


_Generated from first-party honeypot capture. CC BY 4.0._
