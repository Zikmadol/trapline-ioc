# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2322 attackers** · **459,258 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 15 |
| Seen on more than one sensor | 165 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 943 |
| `ssh-bruteforce` | 536 |
| `redis-exploit` | 438 |
| `canary-aws-key` | 346 |
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
| `ssh` | 1528 |
| `redis` | 451 |
| `mcp` | 255 |
| `llamacpp` | 140 |
| `jupyter` | 88 |
| `vllm` | 88 |
| `litellm` | 79 |
| `hfhub` | 71 |
| `docker` | 62 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 877 |
| `345gs5662d34` | 752 |
| `admin` | 507 |
| `ubuntu` | 246 |
| `user` | 122 |
| `ftpuser` | 115 |
| `test` | 113 |
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
| `345gs5662d34` | 751 |
| `3245gs5662d34` | 748 |
| `123456` | 579 |
| `123` | 367 |
| `1234` | 287 |
| `12345678` | 191 |
| `admin` | 184 |
| `12345` | 178 |
| `1` | 162 |
| `password` | 126 |
| `P@ssw0rd` | 117 |
| `admin123` | 110 |
| `000000` | 98 |
| `123456789` | 96 |
| `!QAZ2wsx` | 87 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1031 |
| `cd` | 880 |
| `echo` | 879 |
| `cat` | 878 |
| `crontab` | 860 |
| `lscpu` | 860 |
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
