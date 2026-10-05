# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1718 attackers** · **367,216 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 119 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 119 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 724 |
| `ssh-bruteforce` | 415 |
| `redis-exploit` | 316 |
| `mcp-abuse` | 109 |
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
| `ssh` | 1170 |
| `redis` | 325 |
| `mcp` | 153 |
| `llamacpp` | 96 |
| `vllm` | 58 |
| `litellm` | 53 |
| `jupyter` | 52 |
| `hfhub` | 47 |
| `docker` | 36 |
| `ollama` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 692 |
| `345gs5662d34` | 580 |
| `admin` | 366 |
| `ubuntu` | 168 |
| `test` | 86 |
| `user` | 83 |
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
| `3245gs5662d34` | 580 |
| `345gs5662d34` | 579 |
| `123456` | 419 |
| `123` | 241 |
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
| `uname` | 777 |
| `echo` | 676 |
| `lscpu` | 662 |
| `crontab` | 661 |
| `cd` | 659 |
| `cat` | 658 |
| `ls` | 598 |
| `top` | 597 |
| `df` | 596 |
| `free` | 596 |
| `whoami` | 595 |
| `w` | 594 |
| `INFO` | 209 |
| `canary_env` | 137 |
| `PING` | 135 |


_Generated from first-party honeypot capture. CC BY 4.0._
