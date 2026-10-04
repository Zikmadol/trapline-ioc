# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1575 attackers** · **343,497 hostile actions** · covering 22 day(s) through 2026-10-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 111 |
| Stage-2 hosts named in payloads | 27 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 666 |
| `ssh-bruteforce` | 372 |
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
| `ssh` | 1068 |
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
| `root` | 634 |
| `345gs5662d34` | 537 |
| `admin` | 330 |
| `ubuntu` | 144 |
| `administrator` | 82 |
| `test` | 72 |
| `user` | 71 |
| `ftpuser` | 65 |
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
| `3245gs5662d34` | 538 |
| `345gs5662d34` | 536 |
| `123456` | 366 |
| `123` | 220 |
| `1234` | 187 |
| `12345678` | 114 |
| `admin` | 112 |
| `1` | 92 |
| `12345` | 91 |
| `password` | 88 |
| `000000` | 77 |
| `123456789` | 64 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 703 |
| `echo` | 623 |
| `lscpu` | 610 |
| `crontab` | 609 |
| `cd` | 600 |
| `cat` | 600 |
| `ls` | 555 |
| `top` | 554 |
| `df` | 553 |
| `free` | 553 |
| `whoami` | 552 |
| `w` | 551 |
| `INFO` | 197 |
| `canary_env` | 127 |
| `PING` | 127 |


_Generated from first-party honeypot capture. CC BY 4.0._
