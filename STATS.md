# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2091 attackers** · **420,069 hostile actions** · covering 28 day(s) through 2026-10-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 143 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 144 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 863 |
| `ssh-bruteforce` | 489 |
| `redis-exploit` | 390 |
| `mcp-abuse` | 154 |
| `llamacpp-abuse` | 44 |
| `litellm-key-replay` | 31 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 18 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1392 |
| `redis` | 401 |
| `mcp` | 213 |
| `llamacpp` | 121 |
| `jupyter` | 75 |
| `vllm` | 75 |
| `litellm` | 66 |
| `hfhub` | 60 |
| `docker` | 46 |
| `ollama` | 42 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 803 |
| `345gs5662d34` | 695 |
| `admin` | 453 |
| `ubuntu` | 210 |
| `test` | 105 |
| `user` | 105 |
| `ftpuser` | 98 |
| `administrator` | 75 |
| `git` | 68 |
| `postgres` | 60 |
| `deploy` | 59 |
| `guest` | 57 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 695 |
| `345gs5662d34` | 694 |
| `123456` | 513 |
| `123` | 316 |
| `1234` | 262 |
| `12345678` | 173 |
| `admin` | 166 |
| `12345` | 160 |
| `1` | 146 |
| `password` | 113 |
| `P@ssw0rd` | 99 |
| `000000` | 93 |
| `admin123` | 93 |
| `123456789` | 87 |
| `!QAZ2wsx` | 81 |

### Top commands run

| command | times |
|---|---|
| `uname` | 940 |
| `echo` | 812 |
| `cd` | 797 |
| `crontab` | 795 |
| `lscpu` | 795 |
| `cat` | 795 |
| `ls` | 715 |
| `top` | 714 |
| `df` | 713 |
| `free` | 713 |
| `whoami` | 712 |
| `w` | 711 |
| `INFO` | 261 |
| `canary_env` | 188 |
| `PING` | 180 |


_Generated from first-party honeypot capture. CC BY 4.0._
