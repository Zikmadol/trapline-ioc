# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2452 attackers** · **477,961 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 165 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 175 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 989 |
| `canary-aws-key` | 793 |
| `ssh-bruteforce` | 570 |
| `redis-exploit` | 469 |
| `mcp-abuse` | 190 |
| `llamacpp-abuse` | 53 |
| `litellm-key-replay` | 37 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1611 |
| `redis` | 482 |
| `mcp` | 266 |
| `llamacpp` | 155 |
| `vllm` | 98 |
| `jupyter` | 94 |
| `litellm` | 88 |
| `hfhub` | 75 |
| `docker` | 66 |
| `ollama` | 47 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 923 |
| `345gs5662d34` | 789 |
| `admin` | 535 |
| `ubuntu` | 254 |
| `user` | 129 |
| `ftpuser` | 121 |
| `test` | 118 |
| `git` | 81 |
| `administrator` | 80 |
| `postgres` | 78 |
| `deploy` | 78 |
| `guest` | 75 |
| `oracle` | 62 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 788 |
| `3245gs5662d34` | 785 |
| `123456` | 623 |
| `123` | 390 |
| `1234` | 302 |
| `12345678` | 211 |
| `admin` | 198 |
| `12345` | 189 |
| `1` | 173 |
| `password` | 133 |
| `P@ssw0rd` | 128 |
| `admin123` | 123 |
| `123456789` | 102 |
| `000000` | 101 |
| `!QAZ2wsx` | 92 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1090 |
| `cd` | 926 |
| `echo` | 926 |
| `cat` | 924 |
| `crontab` | 907 |
| `lscpu` | 906 |
| `ls` | 811 |
| `free` | 810 |
| `top` | 809 |
| `df` | 808 |
| `w` | 807 |
| `whoami` | 807 |
| `INFO` | 311 |
| `canary_env` | 226 |
| `PING` | 208 |


_Generated from first-party honeypot capture. CC BY 4.0._
