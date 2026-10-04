# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1584 attackers** · **346,358 hostile actions** · covering 22 day(s) through 2026-10-04

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
| `ssh-bruteforce` | 372 |
| `redis-exploit` | 300 |
| `mcp-abuse` | 102 |
| `llamacpp-abuse` | 28 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `llamacpp-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1072 |
| `redis` | 309 |
| `mcp` | 144 |
| `llamacpp` | 91 |
| `vllm` | 57 |
| `jupyter` | 49 |
| `litellm` | 49 |
| `hfhub` | 44 |
| `docker` | 35 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 636 |
| `345gs5662d34` | 539 |
| `admin` | 330 |
| `ubuntu` | 146 |
| `administrator` | 81 |
| `user` | 75 |
| `test` | 72 |
| `ftpuser` | 67 |
| `admin1` | 60 |
| `AdminGPON` | 55 |
| `a` | 53 |
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
| `1` | 98 |
| `12345` | 93 |
| `password` | 90 |
| `000000` | 77 |
| `123456789` | 65 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `P@ssw0rd` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 708 |
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
| `INFO` | 198 |
| `canary_env` | 129 |
| `PING` | 128 |


_Generated from first-party honeypot capture. CC BY 4.0._
