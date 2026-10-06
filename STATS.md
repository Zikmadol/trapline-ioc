# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1734 attackers** · **367,939 hostile actions** · covering 24 day(s) through 2026-10-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 119 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 119 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 729 |
| `ssh-bruteforce` | 419 |
| `redis-exploit` | 321 |
| `mcp-abuse` | 110 |
| `llamacpp-abuse` | 33 |
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
| `ssh` | 1179 |
| `redis` | 331 |
| `mcp` | 156 |
| `llamacpp` | 98 |
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
| `root` | 697 |
| `345gs5662d34` | 585 |
| `admin` | 371 |
| `ubuntu` | 172 |
| `test` | 86 |
| `user` | 86 |
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
| `3245gs5662d34` | 585 |
| `345gs5662d34` | 584 |
| `123456` | 424 |
| `123` | 246 |
| `1234` | 210 |
| `12345678` | 134 |
| `admin` | 128 |
| `1` | 111 |
| `12345` | 109 |
| `password` | 97 |
| `000000` | 84 |
| `123456789` | 70 |
| `P@ssw0rd` | 70 |
| `!QAZ2wsx` | 69 |
| `!qaz@WSX` | 64 |

### Top commands run

| command | times |
|---|---|
| `uname` | 784 |
| `echo` | 681 |
| `lscpu` | 667 |
| `crontab` | 666 |
| `cd` | 666 |
| `cat` | 665 |
| `ls` | 603 |
| `top` | 602 |
| `df` | 601 |
| `free` | 601 |
| `whoami` | 600 |
| `w` | 599 |
| `INFO` | 213 |
| `canary_env` | 139 |
| `PING` | 139 |


_Generated from first-party honeypot capture. CC BY 4.0._
