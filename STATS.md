# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2295 attackers** · **457,480 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 14 |
| Seen on more than one sensor | 164 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 936 |
| `ssh-bruteforce` | 533 |
| `redis-exploit` | 429 |
| `canary-aws-key` | 253 |
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
| `redis` | 442 |
| `mcp` | 249 |
| `llamacpp` | 140 |
| `jupyter` | 88 |
| `vllm` | 88 |
| `litellm` | 78 |
| `hfhub` | 69 |
| `docker` | 59 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 870 |
| `345gs5662d34` | 748 |
| `admin` | 500 |
| `ubuntu` | 246 |
| `user` | 123 |
| `ftpuser` | 113 |
| `test` | 110 |
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
| `123456` | 572 |
| `123` | 365 |
| `1234` | 284 |
| `12345678` | 189 |
| `admin` | 183 |
| `12345` | 177 |
| `1` | 161 |
| `password` | 125 |
| `P@ssw0rd` | 115 |
| `admin123` | 108 |
| `000000` | 98 |
| `123456789` | 94 |
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
| `INFO` | 288 |
| `canary_env` | 216 |
| `PING` | 192 |


_Generated from first-party honeypot capture. CC BY 4.0._
