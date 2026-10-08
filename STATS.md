# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1971 attackers** · **398,775 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 137 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 135 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 818 |
| `ssh-bruteforce` | 465 |
| `redis-exploit` | 367 |
| `mcp-abuse` | 135 |
| `llamacpp-abuse` | 42 |
| `litellm-key-replay` | 29 |
| `ollama-abuse` | 25 |
| `canary-aws-key` | 17 |
| `docker-abuse` | 16 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 9 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1321 |
| `redis` | 378 |
| `mcp` | 189 |
| `llamacpp` | 115 |
| `vllm` | 68 |
| `jupyter` | 67 |
| `litellm` | 60 |
| `hfhub` | 54 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 768 |
| `345gs5662d34` | 659 |
| `admin` | 427 |
| `ubuntu` | 199 |
| `test` | 102 |
| `user` | 101 |
| `ftpuser` | 87 |
| `administrator` | 74 |
| `git` | 58 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `postgres` | 54 |
| `deploy` | 53 |
| `debian` | 51 |
| `guest` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 659 |
| `345gs5662d34` | 658 |
| `123456` | 478 |
| `123` | 290 |
| `1234` | 242 |
| `12345678` | 159 |
| `admin` | 153 |
| `12345` | 138 |
| `1` | 128 |
| `password` | 112 |
| `P@ssw0rd` | 89 |
| `000000` | 88 |
| `123456789` | 83 |
| `admin123` | 82 |
| `!QAZ2wsx` | 76 |

### Top commands run

| command | times |
|---|---|
| `uname` | 889 |
| `echo` | 767 |
| `cd` | 754 |
| `cat` | 752 |
| `lscpu` | 751 |
| `crontab` | 750 |
| `ls` | 677 |
| `top` | 676 |
| `df` | 675 |
| `free` | 675 |
| `whoami` | 674 |
| `w` | 673 |
| `INFO` | 244 |
| `canary_env` | 169 |
| `PING` | 165 |


_Generated from first-party honeypot capture. CC BY 4.0._
