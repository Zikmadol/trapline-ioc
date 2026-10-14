# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2362 attackers** · **465,815 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 158 |
| Used a planted canary credential | 16 |
| Seen on more than one sensor | 170 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 963 |
| `ssh-bruteforce` | 544 |
| `canary-aws-key` | 529 |
| `redis-exploit` | 445 |
| `mcp-abuse` | 186 |
| `llamacpp-abuse` | 49 |
| `litellm-key-replay` | 35 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1559 |
| `redis` | 458 |
| `mcp` | 256 |
| `llamacpp` | 145 |
| `vllm` | 93 |
| `jupyter` | 91 |
| `litellm` | 84 |
| `hfhub` | 71 |
| `docker` | 64 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 894 |
| `345gs5662d34` | 767 |
| `admin` | 519 |
| `ubuntu` | 252 |
| `user` | 124 |
| `test` | 115 |
| `ftpuser` | 115 |
| `postgres` | 79 |
| `git` | 79 |
| `administrator` | 78 |
| `guest` | 71 |
| `deploy` | 71 |
| `oracle` | 60 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 766 |
| `3245gs5662d34` | 763 |
| `123456` | 595 |
| `123` | 380 |
| `1234` | 290 |
| `12345678` | 198 |
| `admin` | 187 |
| `12345` | 180 |
| `1` | 167 |
| `password` | 128 |
| `P@ssw0rd` | 121 |
| `admin123` | 113 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 90 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1054 |
| `cd` | 900 |
| `cat` | 898 |
| `echo` | 898 |
| `crontab` | 879 |
| `lscpu` | 878 |
| `ls` | 789 |
| `free` | 788 |
| `top` | 787 |
| `df` | 786 |
| `w` | 785 |
| `whoami` | 785 |
| `INFO` | 296 |
| `canary_env` | 222 |
| `PING` | 198 |


_Generated from first-party honeypot capture. CC BY 4.0._
