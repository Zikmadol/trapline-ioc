# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2294 attackers** · **456,861 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 14 |
| Seen on more than one sensor | 164 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 937 |
| `ssh-bruteforce` | 532 |
| `redis-exploit` | 428 |
| `canary-aws-key` | 215 |
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
| `ssh` | 1517 |
| `redis` | 441 |
| `mcp` | 249 |
| `llamacpp` | 140 |
| `jupyter` | 88 |
| `vllm` | 87 |
| `litellm` | 78 |
| `hfhub` | 69 |
| `docker` | 59 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 869 |
| `345gs5662d34` | 748 |
| `admin` | 501 |
| `ubuntu` | 246 |
| `user` | 123 |
| `ftpuser` | 113 |
| `test` | 109 |
| `administrator` | 79 |
| `postgres` | 77 |
| `git` | 77 |
| `guest` | 69 |
| `deploy` | 67 |
| `admin1` | 59 |
| `AdminGPON` | 57 |
| `oracle` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 747 |
| `3245gs5662d34` | 744 |
| `123456` | 573 |
| `123` | 366 |
| `1234` | 285 |
| `12345678` | 190 |
| `admin` | 183 |
| `12345` | 178 |
| `1` | 161 |
| `password` | 125 |
| `P@ssw0rd` | 115 |
| `admin123` | 108 |
| `000000` | 98 |
| `123456789` | 95 |
| `!QAZ2wsx` | 87 |

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
| `INFO` | 287 |
| `canary_env` | 216 |
| `PING` | 192 |


_Generated from first-party honeypot capture. CC BY 4.0._
