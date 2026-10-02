# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1404 attackers** · **321,759 hostile actions** · covering 20 day(s) through 2026-10-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 96 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 98 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 597 |
| `ssh-bruteforce` | 334 |
| `redis-exploit` | 268 |
| `mcp-abuse` | 89 |
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
| `ssh` | 957 |
| `redis` | 276 |
| `mcp` | 126 |
| `llamacpp` | 80 |
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
| `root` | 566 |
| `345gs5662d34` | 480 |
| `admin` | 294 |
| `ubuntu` | 130 |
| `administrator` | 89 |
| `admin1` | 67 |
| `user` | 62 |
| `test` | 61 |
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
| `3245gs5662d34` | 483 |
| `345gs5662d34` | 480 |
| `123456` | 306 |
| `123` | 184 |
| `1234` | 160 |
| `12345678` | 94 |
| `admin` | 89 |
| `password` | 75 |
| `000000` | 73 |
| `12345` | 72 |
| `1` | 71 |
| `!QAZ2wsx` | 63 |
| `0` | 60 |
| `123456789` | 58 |
| `0000` | 56 |

### Top commands run

| command | times |
|---|---|
| `uname` | 626 |
| `echo` | 557 |
| `lscpu` | 544 |
| `crontab` | 543 |
| `cd` | 536 |
| `cat` | 536 |
| `ls` | 495 |
| `top` | 495 |
| `df` | 494 |
| `free` | 494 |
| `whoami` | 493 |
| `w` | 492 |
| `INFO` | 178 |
| `canary_env` | 112 |
| `PING` | 111 |


_Generated from first-party honeypot capture. CC BY 4.0._
