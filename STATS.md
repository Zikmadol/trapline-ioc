# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2084 attackers** · **419,507 hostile actions** · covering 28 day(s) through 2026-10-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 143 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 141 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 860 |
| `ssh-bruteforce` | 489 |
| `redis-exploit` | 387 |
| `mcp-abuse` | 152 |
| `llamacpp-abuse` | 44 |
| `litellm-key-replay` | 32 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 18 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1388 |
| `redis` | 399 |
| `mcp` | 211 |
| `llamacpp` | 120 |
| `vllm` | 75 |
| `jupyter` | 74 |
| `litellm` | 66 |
| `hfhub` | 60 |
| `docker` | 45 |
| `ollama` | 42 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 803 |
| `345gs5662d34` | 695 |
| `admin` | 451 |
| `ubuntu` | 209 |
| `test` | 105 |
| `user` | 105 |
| `ftpuser` | 97 |
| `administrator` | 75 |
| `git` | 68 |
| `postgres` | 60 |
| `deploy` | 59 |
| `guest` | 56 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 695 |
| `345gs5662d34` | 694 |
| `123456` | 510 |
| `123` | 315 |
| `1234` | 261 |
| `12345678` | 172 |
| `admin` | 165 |
| `12345` | 159 |
| `1` | 146 |
| `password` | 113 |
| `P@ssw0rd` | 98 |
| `000000` | 93 |
| `admin123` | 91 |
| `123456789` | 87 |
| `!QAZ2wsx` | 81 |

### Top commands run

| command | times |
|---|---|
| `uname` | 937 |
| `echo` | 812 |
| `crontab` | 795 |
| `lscpu` | 795 |
| `cd` | 794 |
| `cat` | 792 |
| `ls` | 715 |
| `top` | 714 |
| `df` | 713 |
| `free` | 713 |
| `whoami` | 712 |
| `w` | 711 |
| `INFO` | 259 |
| `canary_env` | 186 |
| `PING` | 178 |


_Generated from first-party honeypot capture. CC BY 4.0._
