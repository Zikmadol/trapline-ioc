# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2317 attackers** · **459,037 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 15 |
| Seen on more than one sensor | 165 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 941 |
| `ssh-bruteforce` | 536 |
| `redis-exploit` | 438 |
| `canary-aws-key` | 342 |
| `mcp-abuse` | 184 |
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
| `ssh` | 1526 |
| `redis` | 451 |
| `mcp` | 254 |
| `llamacpp` | 140 |
| `jupyter` | 88 |
| `vllm` | 88 |
| `litellm` | 78 |
| `hfhub` | 71 |
| `docker` | 62 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 876 |
| `345gs5662d34` | 751 |
| `admin` | 505 |
| `ubuntu` | 246 |
| `user` | 122 |
| `ftpuser` | 115 |
| `test` | 112 |
| `administrator` | 79 |
| `git` | 78 |
| `postgres` | 77 |
| `guest` | 71 |
| `deploy` | 67 |
| `admin1` | 59 |
| `AdminGPON` | 57 |
| `oracle` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 750 |
| `3245gs5662d34` | 747 |
| `123456` | 577 |
| `123` | 365 |
| `1234` | 287 |
| `12345678` | 191 |
| `admin` | 184 |
| `12345` | 178 |
| `1` | 162 |
| `password` | 125 |
| `P@ssw0rd` | 117 |
| `admin123` | 109 |
| `000000` | 98 |
| `123456789` | 96 |
| `!QAZ2wsx` | 87 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1029 |
| `echo` | 878 |
| `cd` | 877 |
| `cat` | 876 |
| `crontab` | 859 |
| `lscpu` | 859 |
| `ls` | 772 |
| `free` | 771 |
| `top` | 771 |
| `df` | 770 |
| `whoami` | 769 |
| `w` | 768 |
| `INFO` | 295 |
| `canary_env` | 220 |
| `PING` | 197 |


_Generated from first-party honeypot capture. CC BY 4.0._
