# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2330 attackers** · **460,739 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 156 |
| Used a planted canary credential | 15 |
| Seen on more than one sensor | 165 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 944 |
| `ssh-bruteforce` | 543 |
| `redis-exploit` | 438 |
| `canary-aws-key` | 347 |
| `mcp-abuse` | 185 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 34 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1536 |
| `redis` | 451 |
| `mcp` | 255 |
| `llamacpp` | 140 |
| `jupyter` | 88 |
| `vllm` | 88 |
| `litellm` | 80 |
| `hfhub` | 71 |
| `docker` | 62 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 883 |
| `345gs5662d34` | 752 |
| `admin` | 511 |
| `ubuntu` | 247 |
| `user` | 122 |
| `test` | 115 |
| `ftpuser` | 115 |
| `administrator` | 79 |
| `git` | 78 |
| `postgres` | 77 |
| `guest` | 71 |
| `deploy` | 68 |
| `admin1` | 59 |
| `oracle` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 751 |
| `3245gs5662d34` | 748 |
| `123456` | 581 |
| `123` | 372 |
| `1234` | 288 |
| `12345678` | 194 |
| `admin` | 185 |
| `12345` | 179 |
| `1` | 162 |
| `password` | 127 |
| `P@ssw0rd` | 119 |
| `admin123` | 111 |
| `000000` | 99 |
| `123456789` | 96 |
| `!QAZ2wsx` | 88 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1033 |
| `cd` | 881 |
| `echo` | 880 |
| `cat` | 879 |
| `crontab` | 861 |
| `lscpu` | 861 |
| `ls` | 773 |
| `free` | 772 |
| `top` | 772 |
| `df` | 771 |
| `whoami` | 770 |
| `w` | 769 |
| `INFO` | 295 |
| `canary_env` | 221 |
| `PING` | 197 |


_Generated from first-party honeypot capture. CC BY 4.0._
