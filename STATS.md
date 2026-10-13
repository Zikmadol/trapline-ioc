# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2290 attackers** · **456,609 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 14 |
| Seen on more than one sensor | 163 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 937 |
| `ssh-bruteforce` | 529 |
| `redis-exploit` | 427 |
| `canary-aws-key` | 197 |
| `mcp-abuse` | 180 |
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
| `ssh` | 1513 |
| `redis` | 440 |
| `mcp` | 248 |
| `llamacpp` | 140 |
| `jupyter` | 87 |
| `vllm` | 87 |
| `litellm` | 78 |
| `hfhub` | 69 |
| `docker` | 59 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 867 |
| `345gs5662d34` | 748 |
| `admin` | 499 |
| `ubuntu` | 245 |
| `user` | 123 |
| `ftpuser` | 112 |
| `test` | 108 |
| `administrator` | 79 |
| `git` | 77 |
| `postgres` | 75 |
| `guest` | 69 |
| `deploy` | 68 |
| `admin1` | 59 |
| `AdminGPON` | 57 |
| `oracle` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 747 |
| `3245gs5662d34` | 744 |
| `123456` | 572 |
| `123` | 366 |
| `1234` | 285 |
| `12345678` | 190 |
| `admin` | 182 |
| `12345` | 178 |
| `1` | 161 |
| `password` | 124 |
| `P@ssw0rd` | 115 |
| `admin123` | 108 |
| `000000` | 98 |
| `123456789` | 95 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1023 |
| `echo` | 874 |
| `cd` | 872 |
| `cat` | 871 |
| `crontab` | 855 |
| `lscpu` | 855 |
| `ls` | 768 |
| `free` | 767 |
| `top` | 767 |
| `df` | 766 |
| `whoami` | 765 |
| `w` | 764 |
| `INFO` | 286 |
| `canary_env` | 216 |
| `PING` | 192 |


_Generated from first-party honeypot capture. CC BY 4.0._
