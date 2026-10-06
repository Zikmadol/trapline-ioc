# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1743 attackers** · **369,384 hostile actions** · covering 24 day(s) through 2026-10-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 121 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 119 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 732 |
| `ssh-bruteforce` | 420 |
| `redis-exploit` | 322 |
| `mcp-abuse` | 111 |
| `llamacpp-abuse` | 36 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1183 |
| `redis` | 332 |
| `mcp` | 157 |
| `llamacpp` | 101 |
| `vllm` | 59 |
| `litellm` | 54 |
| `jupyter` | 52 |
| `hfhub` | 48 |
| `docker` | 36 |
| `ollama` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 698 |
| `345gs5662d34` | 586 |
| `admin` | 372 |
| `ubuntu` | 172 |
| `user` | 87 |
| `test` | 86 |
| `administrator` | 79 |
| `ftpuser` | 75 |
| `admin1` | 57 |
| `AdminGPON` | 56 |
| `a` | 53 |
| `admin2` | 53 |
| `Asalem` | 51 |
| `Caps` | 50 |
| `git` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 586 |
| `345gs5662d34` | 585 |
| `123456` | 424 |
| `123` | 246 |
| `1234` | 210 |
| `12345678` | 134 |
| `admin` | 130 |
| `1` | 111 |
| `12345` | 109 |
| `password` | 97 |
| `000000` | 84 |
| `P@ssw0rd` | 73 |
| `123456789` | 71 |
| `!QAZ2wsx` | 69 |
| `!qaz@WSX` | 64 |

### Top commands run

| command | times |
|---|---|
| `uname` | 787 |
| `echo` | 684 |
| `lscpu` | 670 |
| `crontab` | 669 |
| `cd` | 667 |
| `cat` | 666 |
| `ls` | 604 |
| `top` | 603 |
| `df` | 602 |
| `free` | 602 |
| `whoami` | 601 |
| `w` | 600 |
| `INFO` | 214 |
| `canary_env` | 140 |
| `PING` | 140 |


_Generated from first-party honeypot capture. CC BY 4.0._
