# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2102 attackers** · **424,573 hostile actions** · covering 28 day(s) through 2026-10-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 145 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 145 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 868 |
| `ssh-bruteforce` | 489 |
| `redis-exploit` | 391 |
| `mcp-abuse` | 156 |
| `llamacpp-abuse` | 44 |
| `litellm-key-replay` | 31 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 21 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1397 |
| `redis` | 402 |
| `mcp` | 215 |
| `llamacpp` | 122 |
| `jupyter` | 75 |
| `vllm` | 75 |
| `litellm` | 66 |
| `hfhub` | 60 |
| `docker` | 49 |
| `ollama` | 42 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 806 |
| `345gs5662d34` | 699 |
| `admin` | 456 |
| `ubuntu` | 213 |
| `user` | 107 |
| `test` | 105 |
| `ftpuser` | 98 |
| `administrator` | 76 |
| `git` | 69 |
| `postgres` | 61 |
| `guest` | 60 |
| `deploy` | 60 |
| `AdminGPON` | 56 |
| `admin1` | 56 |
| `debian` | 54 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 699 |
| `345gs5662d34` | 698 |
| `123456` | 515 |
| `123` | 321 |
| `1234` | 263 |
| `12345678` | 173 |
| `admin` | 167 |
| `12345` | 161 |
| `1` | 148 |
| `password` | 113 |
| `P@ssw0rd` | 100 |
| `000000` | 93 |
| `admin123` | 93 |
| `123456789` | 89 |
| `!QAZ2wsx` | 82 |

### Top commands run

| command | times |
|---|---|
| `uname` | 945 |
| `echo` | 817 |
| `cd` | 801 |
| `crontab` | 800 |
| `lscpu` | 800 |
| `cat` | 799 |
| `ls` | 719 |
| `top` | 718 |
| `df` | 717 |
| `free` | 717 |
| `whoami` | 716 |
| `w` | 715 |
| `INFO` | 261 |
| `canary_env` | 190 |
| `PING` | 180 |


_Generated from first-party honeypot capture. CC BY 4.0._
