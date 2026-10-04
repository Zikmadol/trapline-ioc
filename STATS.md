# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1580 attackers** · **345,033 hostile actions** · covering 22 day(s) through 2026-10-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 112 |
| Stage-2 hosts named in payloads | 27 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 670 |
| `ssh-bruteforce` | 371 |
| `redis-exploit` | 299 |
| `mcp-abuse` | 101 |
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
| `ssh` | 1071 |
| `redis` | 308 |
| `mcp` | 143 |
| `llamacpp` | 89 |
| `vllm` | 56 |
| `jupyter` | 48 |
| `litellm` | 48 |
| `hfhub` | 43 |
| `docker` | 35 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 636 |
| `345gs5662d34` | 539 |
| `admin` | 330 |
| `ubuntu` | 147 |
| `administrator` | 81 |
| `user` | 75 |
| `test` | 72 |
| `ftpuser` | 67 |
| `admin1` | 60 |
| `AdminGPON` | 55 |
| `a` | 54 |
| `Asalem` | 51 |
| `aaa` | 51 |
| `admin2` | 51 |
| `adminuser` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 540 |
| `345gs5662d34` | 538 |
| `123456` | 372 |
| `123` | 225 |
| `1234` | 188 |
| `12345678` | 114 |
| `admin` | 112 |
| `1` | 97 |
| `12345` | 93 |
| `password` | 90 |
| `000000` | 77 |
| `123456789` | 64 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `P@ssw0rd` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 707 |
| `echo` | 625 |
| `lscpu` | 612 |
| `crontab` | 611 |
| `cat` | 604 |
| `cd` | 603 |
| `ls` | 557 |
| `top` | 556 |
| `df` | 555 |
| `free` | 555 |
| `whoami` | 554 |
| `w` | 553 |
| `INFO` | 197 |
| `canary_env` | 128 |
| `PING` | 127 |


_Generated from first-party honeypot capture. CC BY 4.0._
