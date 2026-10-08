# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1981 attackers** · **400,936 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 138 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 136 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 820 |
| `ssh-bruteforce` | 469 |
| `redis-exploit` | 367 |
| `mcp-abuse` | 139 |
| `llamacpp-abuse` | 42 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 25 |
| `canary-aws-key` | 17 |
| `docker-abuse` | 16 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 9 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1327 |
| `redis` | 378 |
| `mcp` | 193 |
| `llamacpp` | 115 |
| `jupyter` | 68 |
| `vllm` | 68 |
| `litellm` | 60 |
| `hfhub` | 54 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 771 |
| `345gs5662d34` | 660 |
| `admin` | 430 |
| `ubuntu` | 199 |
| `test` | 102 |
| `user` | 102 |
| `ftpuser` | 87 |
| `administrator` | 75 |
| `git` | 59 |
| `AdminGPON` | 56 |
| `deploy` | 56 |
| `postgres` | 55 |
| `admin1` | 55 |
| `guest` | 52 |
| `debian` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 660 |
| `345gs5662d34` | 659 |
| `123456` | 480 |
| `123` | 292 |
| `1234` | 243 |
| `12345678` | 160 |
| `admin` | 154 |
| `12345` | 140 |
| `1` | 134 |
| `password` | 112 |
| `P@ssw0rd` | 90 |
| `000000` | 88 |
| `123456789` | 84 |
| `admin123` | 82 |
| `!QAZ2wsx` | 77 |

### Top commands run

| command | times |
|---|---|
| `uname` | 891 |
| `echo` | 769 |
| `cd` | 755 |
| `lscpu` | 753 |
| `cat` | 753 |
| `crontab` | 752 |
| `ls` | 678 |
| `top` | 677 |
| `df` | 676 |
| `free` | 676 |
| `whoami` | 675 |
| `w` | 674 |
| `INFO` | 244 |
| `canary_env` | 173 |
| `PING` | 165 |


_Generated from first-party honeypot capture. CC BY 4.0._
