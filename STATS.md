# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2043 attackers** · **415,158 hostile actions** · covering 27 day(s) through 2026-10-09

| signal | count |
|---|---|
| GPU / AI-hardware probing | 142 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 139 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 848 |
| `ssh-bruteforce` | 481 |
| `redis-exploit` | 376 |
| `mcp-abuse` | 145 |
| `llamacpp-abuse` | 42 |
| `litellm-key-replay` | 30 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 18 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1368 |
| `redis` | 388 |
| `mcp` | 201 |
| `llamacpp` | 117 |
| `jupyter` | 72 |
| `vllm` | 72 |
| `litellm` | 62 |
| `hfhub` | 57 |
| `docker` | 45 |
| `ollama` | 40 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 792 |
| `345gs5662d34` | 683 |
| `admin` | 444 |
| `ubuntu` | 211 |
| `test` | 103 |
| `user` | 103 |
| `ftpuser` | 92 |
| `administrator` | 75 |
| `git` | 64 |
| `postgres` | 60 |
| `deploy` | 58 |
| `AdminGPON` | 56 |
| `guest` | 55 |
| `admin1` | 55 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 683 |
| `345gs5662d34` | 682 |
| `123456` | 503 |
| `123` | 303 |
| `1234` | 253 |
| `12345678` | 166 |
| `admin` | 161 |
| `12345` | 152 |
| `1` | 143 |
| `password` | 115 |
| `000000` | 93 |
| `P@ssw0rd` | 93 |
| `admin123` | 89 |
| `123456789` | 85 |
| `!QAZ2wsx` | 80 |

### Top commands run

| command | times |
|---|---|
| `uname` | 923 |
| `echo` | 799 |
| `crontab` | 782 |
| `lscpu` | 782 |
| `cd` | 781 |
| `cat` | 779 |
| `ls` | 703 |
| `top` | 702 |
| `df` | 701 |
| `free` | 701 |
| `whoami` | 700 |
| `w` | 699 |
| `INFO` | 252 |
| `canary_env` | 179 |
| `PING` | 171 |


_Generated from first-party honeypot capture. CC BY 4.0._
