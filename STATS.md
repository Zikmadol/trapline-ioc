# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2380 attackers** · **468,377 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 159 |
| Used a planted canary credential | 16 |
| Seen on more than one sensor | 171 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 967 |
| `canary-aws-key` | 654 |
| `ssh-bruteforce` | 547 |
| `redis-exploit` | 453 |
| `mcp-abuse` | 187 |
| `llamacpp-abuse` | 51 |
| `litellm-key-replay` | 35 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1566 |
| `redis` | 466 |
| `mcp` | 259 |
| `llamacpp` | 149 |
| `vllm` | 96 |
| `jupyter` | 93 |
| `litellm` | 85 |
| `hfhub` | 73 |
| `docker` | 64 |
| `ollama` | 46 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 900 |
| `345gs5662d34` | 769 |
| `admin` | 524 |
| `ubuntu` | 252 |
| `user` | 126 |
| `ftpuser` | 118 |
| `test` | 114 |
| `administrator` | 82 |
| `postgres` | 79 |
| `git` | 79 |
| `guest` | 72 |
| `deploy` | 72 |
| `oracle` | 61 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 768 |
| `3245gs5662d34` | 765 |
| `123456` | 601 |
| `123` | 381 |
| `1234` | 292 |
| `12345678` | 200 |
| `admin` | 189 |
| `12345` | 181 |
| `1` | 169 |
| `password` | 129 |
| `P@ssw0rd` | 122 |
| `admin123` | 115 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 90 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1059 |
| `cd` | 904 |
| `cat` | 902 |
| `echo` | 900 |
| `crontab` | 881 |
| `lscpu` | 880 |
| `ls` | 791 |
| `free` | 790 |
| `top` | 789 |
| `df` | 788 |
| `w` | 787 |
| `whoami` | 787 |
| `INFO` | 302 |
| `canary_env` | 223 |
| `PING` | 202 |


_Generated from first-party honeypot capture. CC BY 4.0._
