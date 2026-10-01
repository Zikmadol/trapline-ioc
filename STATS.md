# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1393 attackers** · **319,718 hostile actions** · covering 19 day(s) through 2026-10-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 94 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 97 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 592 |
| `ssh-bruteforce` | 330 |
| `redis-exploit` | 267 |
| `mcp-abuse` | 88 |
| `llamacpp-abuse` | 25 |
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
| `ssh` | 947 |
| `redis` | 275 |
| `mcp` | 125 |
| `llamacpp` | 78 |
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
| `root` | 562 |
| `345gs5662d34` | 474 |
| `admin` | 292 |
| `ubuntu` | 129 |
| `administrator` | 89 |
| `admin1` | 67 |
| `user` | 62 |
| `test` | 59 |
| `admin2` | 58 |
| `adminuser` | 58 |
| `a` | 57 |
| `ai` | 57 |
| `AdminGPON` | 55 |
| `aaa` | 55 |
| `admin123` | 54 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 476 |
| `345gs5662d34` | 474 |
| `123456` | 301 |
| `123` | 180 |
| `1234` | 158 |
| `12345678` | 93 |
| `admin` | 88 |
| `password` | 72 |
| `1` | 71 |
| `000000` | 71 |
| `12345` | 71 |
| `!QAZ2wsx` | 62 |
| `0` | 59 |
| `123456789` | 57 |
| `0000` | 56 |

### Top commands run

| command | times |
|---|---|
| `uname` | 618 |
| `echo` | 549 |
| `lscpu` | 536 |
| `crontab` | 535 |
| `cd` | 530 |
| `cat` | 530 |
| `ls` | 489 |
| `top` | 489 |
| `df` | 488 |
| `free` | 488 |
| `whoami` | 487 |
| `w` | 486 |
| `INFO` | 177 |
| `canary_env` | 111 |
| `PING` | 110 |


_Generated from first-party honeypot capture. CC BY 4.0._
