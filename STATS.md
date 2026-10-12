# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2245 attackers** · **451,961 hostile actions** · covering 30 day(s) through 2026-10-12

| signal | count |
|---|---|
| GPU / AI-hardware probing | 154 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 159 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 925 |
| `ssh-bruteforce` | 519 |
| `redis-exploit` | 422 |
| `mcp-abuse` | 172 |
| `llamacpp-abuse` | 47 |
| `litellm-key-replay` | 32 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 22 |
| `canary-aws-key` | 19 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1490 |
| `redis` | 434 |
| `mcp` | 237 |
| `llamacpp` | 134 |
| `vllm` | 87 |
| `jupyter` | 83 |
| `litellm` | 74 |
| `hfhub` | 69 |
| `docker` | 54 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 853 |
| `345gs5662d34` | 734 |
| `admin` | 490 |
| `ubuntu` | 237 |
| `user` | 123 |
| `ftpuser` | 110 |
| `test` | 108 |
| `administrator` | 77 |
| `git` | 74 |
| `postgres` | 73 |
| `guest` | 68 |
| `deploy` | 67 |
| `admin1` | 59 |
| `oracle` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 733 |
| `3245gs5662d34` | 730 |
| `123456` | 558 |
| `123` | 357 |
| `1234` | 279 |
| `12345678` | 184 |
| `admin` | 179 |
| `12345` | 175 |
| `1` | 154 |
| `password` | 119 |
| `P@ssw0rd` | 111 |
| `admin123` | 107 |
| `000000` | 98 |
| `123456789` | 89 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1008 |
| `echo` | 858 |
| `cd` | 858 |
| `cat` | 857 |
| `crontab` | 840 |
| `lscpu` | 840 |
| `ls` | 754 |
| `free` | 753 |
| `top` | 753 |
| `df` | 752 |
| `whoami` | 751 |
| `w` | 750 |
| `INFO` | 280 |
| `canary_env` | 207 |
| `PING` | 191 |


_Generated from first-party honeypot capture. CC BY 4.0._
