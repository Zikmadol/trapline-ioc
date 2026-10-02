# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1438 attackers** · **327,196 hostile actions** · covering 20 day(s) through 2026-10-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 101 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 99 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 607 |
| `ssh-bruteforce` | 343 |
| `redis-exploit` | 273 |
| `mcp-abuse` | 92 |
| `llamacpp-abuse` | 26 |
| `litellm-key-replay` | 23 |
| `docker-abuse` | 15 |
| `ollama-abuse` | 12 |
| `canary-aws-key` | 10 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 977 |
| `redis` | 281 |
| `mcp` | 130 |
| `llamacpp` | 81 |
| `vllm` | 50 |
| `litellm` | 43 |
| `jupyter` | 42 |
| `hfhub` | 40 |
| `docker` | 30 |
| `ollama` | 20 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 577 |
| `345gs5662d34` | 489 |
| `admin` | 294 |
| `ubuntu` | 133 |
| `administrator` | 85 |
| `test` | 65 |
| `user` | 64 |
| `admin1` | 63 |
| `AdminGPON` | 55 |
| `ftpuser` | 54 |
| `a` | 54 |
| `admin2` | 54 |
| `adminuser` | 54 |
| `ai` | 53 |
| `aaa` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 491 |
| `345gs5662d34` | 488 |
| `123456` | 313 |
| `123` | 187 |
| `1234` | 163 |
| `12345678` | 98 |
| `admin` | 93 |
| `password` | 77 |
| `1` | 75 |
| `000000` | 74 |
| `12345` | 74 |
| `!QAZ2wsx` | 63 |
| `0` | 61 |
| `123456789` | 58 |
| `0000` | 57 |

### Top commands run

| command | times |
|---|---|
| `uname` | 638 |
| `echo` | 570 |
| `lscpu` | 557 |
| `crontab` | 556 |
| `cd` | 545 |
| `cat` | 545 |
| `ls` | 504 |
| `top` | 504 |
| `df` | 503 |
| `free` | 503 |
| `whoami` | 502 |
| `w` | 501 |
| `INFO` | 180 |
| `canary_env` | 117 |
| `PING` | 112 |


_Generated from first-party honeypot capture. CC BY 4.0._
