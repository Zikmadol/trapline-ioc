# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1428 attackers** · **325,495 hostile actions** · covering 20 day(s) through 2026-10-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 100 |
| Used a planted canary credential | 3 |
| Seen on more than one sensor | 99 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 604 |
| `ssh-bruteforce` | 342 |
| `redis-exploit` | 269 |
| `mcp-abuse` | 92 |
| `llamacpp-abuse` | 25 |
| `litellm-key-replay` | 23 |
| `docker-abuse` | 15 |
| `ollama-abuse` | 12 |
| `vllm-abuse` | 6 |
| `canary-aws-key` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 973 |
| `redis` | 277 |
| `mcp` | 129 |
| `llamacpp` | 80 |
| `vllm` | 49 |
| `litellm` | 43 |
| `jupyter` | 42 |
| `hfhub` | 37 |
| `docker` | 30 |
| `ollama` | 20 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 575 |
| `345gs5662d34` | 486 |
| `admin` | 293 |
| `ubuntu` | 132 |
| `administrator` | 86 |
| `test` | 65 |
| `user` | 64 |
| `admin1` | 64 |
| `AdminGPON` | 55 |
| `a` | 55 |
| `admin2` | 55 |
| `adminuser` | 55 |
| `ai` | 54 |
| `ftpuser` | 53 |
| `aaa` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 489 |
| `345gs5662d34` | 486 |
| `123456` | 311 |
| `123` | 185 |
| `1234` | 162 |
| `12345678` | 95 |
| `admin` | 92 |
| `password` | 76 |
| `1` | 74 |
| `000000` | 74 |
| `12345` | 73 |
| `!QAZ2wsx` | 63 |
| `0` | 61 |
| `123456789` | 58 |
| `0000` | 57 |

### Top commands run

| command | times |
|---|---|
| `uname` | 635 |
| `echo` | 566 |
| `lscpu` | 553 |
| `crontab` | 552 |
| `cd` | 542 |
| `cat` | 542 |
| `ls` | 501 |
| `top` | 501 |
| `df` | 500 |
| `free` | 500 |
| `whoami` | 499 |
| `w` | 498 |
| `INFO` | 179 |
| `canary_env` | 116 |
| `PING` | 112 |


_Generated from first-party honeypot capture. CC BY 4.0._
