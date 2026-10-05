# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1725 attackers** · **367,456 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 119 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 119 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 725 |
| `ssh-bruteforce` | 415 |
| `redis-exploit` | 321 |
| `mcp-abuse` | 110 |
| `llamacpp-abuse` | 32 |
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
| `ssh` | 1171 |
| `redis` | 330 |
| `mcp` | 154 |
| `llamacpp` | 97 |
| `vllm` | 58 |
| `litellm` | 54 |
| `jupyter` | 52 |
| `hfhub` | 48 |
| `docker` | 36 |
| `ollama` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 693 |
| `345gs5662d34` | 581 |
| `admin` | 367 |
| `ubuntu` | 168 |
| `test` | 86 |
| `user` | 84 |
| `administrator` | 79 |
| `ftpuser` | 72 |
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
| `3245gs5662d34` | 581 |
| `345gs5662d34` | 580 |
| `123456` | 420 |
| `123` | 242 |
| `1234` | 210 |
| `12345678` | 132 |
| `admin` | 128 |
| `1` | 111 |
| `12345` | 108 |
| `password` | 97 |
| `000000` | 84 |
| `123456789` | 70 |
| `P@ssw0rd` | 70 |
| `!QAZ2wsx` | 69 |
| `!qaz@WSX` | 64 |

### Top commands run

| command | times |
|---|---|
| `uname` | 778 |
| `echo` | 677 |
| `lscpu` | 663 |
| `crontab` | 662 |
| `cd` | 660 |
| `cat` | 659 |
| `ls` | 599 |
| `top` | 598 |
| `df` | 597 |
| `free` | 597 |
| `whoami` | 596 |
| `w` | 595 |
| `INFO` | 212 |
| `PING` | 139 |
| `canary_env` | 138 |


_Generated from first-party honeypot capture. CC BY 4.0._
