# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1568 attackers** · **342,977 hostile actions** · covering 22 day(s) through 2026-10-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 111 |
| Stage-2 hosts named in payloads | 27 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 661 |
| `ssh-bruteforce` | 370 |
| `redis-exploit` | 298 |
| `mcp-abuse` | 100 |
| `llamacpp-abuse` | 28 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1061 |
| `redis` | 307 |
| `mcp` | 142 |
| `llamacpp` | 89 |
| `vllm` | 56 |
| `jupyter` | 48 |
| `litellm` | 48 |
| `hfhub` | 43 |
| `docker` | 34 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 629 |
| `345gs5662d34` | 533 |
| `admin` | 329 |
| `ubuntu` | 143 |
| `administrator` | 82 |
| `test` | 72 |
| `user` | 72 |
| `ftpuser` | 64 |
| `admin1` | 61 |
| `AdminGPON` | 55 |
| `a` | 54 |
| `aaa` | 52 |
| `admin2` | 52 |
| `adminuser` | 52 |
| `Asalem` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 534 |
| `345gs5662d34` | 532 |
| `123456` | 363 |
| `123` | 216 |
| `1234` | 187 |
| `12345678` | 113 |
| `admin` | 110 |
| `12345` | 89 |
| `1` | 88 |
| `password` | 86 |
| `000000` | 77 |
| `123456789` | 64 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 699 |
| `echo` | 620 |
| `lscpu` | 607 |
| `crontab` | 606 |
| `cd` | 596 |
| `cat` | 596 |
| `ls` | 551 |
| `top` | 551 |
| `df` | 550 |
| `free` | 550 |
| `whoami` | 549 |
| `w` | 548 |
| `INFO` | 197 |
| `canary_env` | 127 |
| `PING` | 127 |


_Generated from first-party honeypot capture. CC BY 4.0._
