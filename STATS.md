# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1275 attackers** · **285,047 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 79 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 85 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 539 |
| `ssh-bruteforce` | 300 |
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
| `ssh` | 860 |
| `redis` | 258 |
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
| `root` | 505 |
| `345gs5662d34` | 434 |
| `admin` | 259 |
| `ubuntu` | 106 |
| `administrator` | 78 |
| `admin1` | 64 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `user` | 49 |
| `admin123` | 49 |
| `Asalem` | 48 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 436 |
| `345gs5662d34` | 434 |
| `123456` | 255 |
| `123` | 144 |
| `1234` | 127 |
| `admin` | 81 |
| `12345678` | 77 |
| `password` | 67 |
| `000000` | 67 |
| `1` | 60 |
| `12345` | 60 |
| `!QAZ2wsx` | 55 |
| `0` | 53 |
| `0000` | 52 |
| `!Q2w3e4r` | 51 |

### Top commands run

| command | times |
|---|---|
| `uname` | 557 |
| `echo` | 498 |
| `lscpu` | 488 |
| `crontab` | 485 |
| `cd` | 483 |
| `cat` | 482 |
| `top` | 449 |
| `ls` | 448 |
| `df` | 448 |
| `free` | 448 |
| `whoami` | 447 |
| `w` | 446 |
| `INFO` | 166 |
| `canary_env` | 100 |
| `PING` | 100 |


_Generated from first-party honeypot capture. CC BY 4.0._
