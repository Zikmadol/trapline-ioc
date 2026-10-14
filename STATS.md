# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2369 attackers** · **467,120 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 158 |
| Used a planted canary credential | 16 |
| Seen on more than one sensor | 171 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 964 |
| `canary-aws-key` | 571 |
| `ssh-bruteforce` | 546 |
| `redis-exploit` | 448 |
| `mcp-abuse` | 186 |
| `llamacpp-abuse` | 50 |
| `litellm-key-replay` | 35 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1562 |
| `redis` | 461 |
| `mcp` | 256 |
| `llamacpp` | 146 |
| `vllm` | 93 |
| `jupyter` | 91 |
| `litellm` | 84 |
| `hfhub` | 71 |
| `docker` | 64 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 895 |
| `345gs5662d34` | 768 |
| `admin` | 521 |
| `ubuntu` | 252 |
| `user` | 124 |
| `ftpuser` | 116 |
| `test` | 115 |
| `postgres` | 79 |
| `administrator` | 79 |
| `git` | 79 |
| `guest` | 72 |
| `deploy` | 71 |
| `oracle` | 60 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 767 |
| `3245gs5662d34` | 764 |
| `123456` | 596 |
| `123` | 380 |
| `1234` | 291 |
| `12345678` | 200 |
| `admin` | 189 |
| `12345` | 181 |
| `1` | 167 |
| `password` | 128 |
| `P@ssw0rd` | 122 |
| `admin123` | 114 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 90 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1055 |
| `cd` | 901 |
| `cat` | 899 |
| `echo` | 899 |
| `crontab` | 880 |
| `lscpu` | 879 |
| `ls` | 790 |
| `free` | 789 |
| `top` | 788 |
| `df` | 787 |
| `w` | 786 |
| `whoami` | 786 |
| `INFO` | 298 |
| `canary_env` | 222 |
| `PING` | 199 |


_Generated from first-party honeypot capture. CC BY 4.0._
