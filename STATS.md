# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2112 attackers** · **428,544 hostile actions** · covering 28 day(s) through 2026-10-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 145 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 148 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 872 |
| `ssh-bruteforce` | 490 |
| `redis-exploit` | 394 |
| `mcp-abuse` | 158 |
| `llamacpp-abuse` | 44 |
| `litellm-key-replay` | 31 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 22 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1405 |
| `redis` | 405 |
| `mcp` | 217 |
| `llamacpp` | 124 |
| `vllm` | 77 |
| `jupyter` | 76 |
| `litellm` | 67 |
| `hfhub` | 63 |
| `docker` | 52 |
| `ollama` | 43 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 806 |
| `345gs5662d34` | 699 |
| `admin` | 461 |
| `ubuntu` | 214 |
| `user` | 107 |
| `test` | 105 |
| `ftpuser` | 98 |
| `administrator` | 76 |
| `git` | 69 |
| `postgres` | 61 |
| `guest` | 60 |
| `deploy` | 60 |
| `AdminGPON` | 57 |
| `admin1` | 56 |
| `debian` | 54 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 699 |
| `345gs5662d34` | 698 |
| `123456` | 516 |
| `123` | 322 |
| `1234` | 263 |
| `12345678` | 174 |
| `admin` | 168 |
| `12345` | 161 |
| `1` | 147 |
| `password` | 113 |
| `P@ssw0rd` | 100 |
| `000000` | 95 |
| `admin123` | 94 |
| `123456789` | 89 |
| `!QAZ2wsx` | 82 |

### Top commands run

| command | times |
|---|---|
| `uname` | 949 |
| `echo` | 817 |
| `cd` | 805 |
| `cat` | 803 |
| `crontab` | 800 |
| `lscpu` | 800 |
| `ls` | 719 |
| `top` | 718 |
| `df` | 717 |
| `free` | 717 |
| `whoami` | 716 |
| `w` | 715 |
| `INFO` | 262 |
| `canary_env` | 191 |
| `PING` | 180 |


_Generated from first-party honeypot capture. CC BY 4.0._
