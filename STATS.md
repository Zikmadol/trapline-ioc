# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2070 attackers** · **418,560 hostile actions** · covering 28 day(s) through 2026-10-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 143 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 141 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 857 |
| `ssh-bruteforce` | 486 |
| `redis-exploit` | 383 |
| `mcp-abuse` | 150 |
| `llamacpp-abuse` | 43 |
| `litellm-key-replay` | 31 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 18 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1382 |
| `redis` | 395 |
| `mcp` | 207 |
| `llamacpp` | 118 |
| `jupyter` | 73 |
| `vllm` | 73 |
| `litellm` | 64 |
| `hfhub` | 58 |
| `docker` | 45 |
| `ollama` | 40 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 801 |
| `345gs5662d34` | 692 |
| `admin` | 448 |
| `ubuntu` | 210 |
| `test` | 104 |
| `user` | 104 |
| `ftpuser` | 97 |
| `administrator` | 75 |
| `git` | 66 |
| `postgres` | 60 |
| `deploy` | 59 |
| `guest` | 56 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 692 |
| `345gs5662d34` | 691 |
| `123456` | 509 |
| `123` | 313 |
| `1234` | 259 |
| `12345678` | 170 |
| `admin` | 162 |
| `12345` | 159 |
| `1` | 146 |
| `password` | 114 |
| `P@ssw0rd` | 97 |
| `000000` | 93 |
| `admin123` | 91 |
| `123456789` | 85 |
| `!QAZ2wsx` | 81 |

### Top commands run

| command | times |
|---|---|
| `uname` | 934 |
| `echo` | 809 |
| `crontab` | 792 |
| `lscpu` | 792 |
| `cd` | 791 |
| `cat` | 789 |
| `ls` | 712 |
| `top` | 711 |
| `df` | 710 |
| `free` | 710 |
| `whoami` | 709 |
| `w` | 708 |
| `INFO` | 255 |
| `canary_env` | 184 |
| `PING` | 176 |


_Generated from first-party honeypot capture. CC BY 4.0._
