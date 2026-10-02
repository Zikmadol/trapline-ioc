# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1442 attackers** · **328,136 hostile actions** · covering 20 day(s) through 2026-10-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 101 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 99 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 608 |
| `ssh-bruteforce` | 343 |
| `redis-exploit` | 276 |
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
| `ssh` | 979 |
| `redis` | 284 |
| `mcp` | 130 |
| `llamacpp` | 81 |
| `vllm` | 50 |
| `jupyter` | 43 |
| `litellm` | 43 |
| `hfhub` | 40 |
| `docker` | 30 |
| `ollama` | 20 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 577 |
| `345gs5662d34` | 489 |
| `admin` | 296 |
| `ubuntu` | 135 |
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
| `123456` | 317 |
| `123` | 189 |
| `1234` | 163 |
| `12345678` | 98 |
| `admin` | 94 |
| `password` | 78 |
| `1` | 75 |
| `000000` | 75 |
| `12345` | 74 |
| `!QAZ2wsx` | 63 |
| `0` | 61 |
| `123456789` | 58 |
| `0000` | 57 |

### Top commands run

| command | times |
|---|---|
| `uname` | 641 |
| `echo` | 570 |
| `lscpu` | 557 |
| `crontab` | 556 |
| `cat` | 547 |
| `cd` | 546 |
| `ls` | 504 |
| `top` | 504 |
| `df` | 503 |
| `free` | 503 |
| `whoami` | 502 |
| `w` | 501 |
| `INFO` | 181 |
| `canary_env` | 117 |
| `PING` | 115 |


_Generated from first-party honeypot capture. CC BY 4.0._
