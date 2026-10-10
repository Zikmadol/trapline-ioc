# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2118 attackers** · **429,386 hostile actions** · covering 28 day(s) through 2026-10-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 145 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 149 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 873 |
| `ssh-bruteforce` | 491 |
| `redis-exploit` | 398 |
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
| `ssh` | 1407 |
| `redis` | 409 |
| `mcp` | 217 |
| `llamacpp` | 125 |
| `jupyter` | 78 |
| `vllm` | 78 |
| `litellm` | 68 |
| `hfhub` | 63 |
| `docker` | 52 |
| `ollama` | 44 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 808 |
| `345gs5662d34` | 700 |
| `admin` | 461 |
| `ubuntu` | 217 |
| `user` | 107 |
| `test` | 104 |
| `ftpuser` | 98 |
| `administrator` | 76 |
| `git` | 69 |
| `guest` | 63 |
| `postgres` | 61 |
| `deploy` | 61 |
| `AdminGPON` | 57 |
| `admin1` | 56 |
| `debian` | 54 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 700 |
| `345gs5662d34` | 699 |
| `123456` | 518 |
| `123` | 324 |
| `1234` | 263 |
| `12345678` | 174 |
| `admin` | 168 |
| `12345` | 163 |
| `1` | 148 |
| `password` | 113 |
| `P@ssw0rd` | 102 |
| `000000` | 96 |
| `admin123` | 94 |
| `123456789` | 89 |
| `!QAZ2wsx` | 82 |

### Top commands run

| command | times |
|---|---|
| `uname` | 950 |
| `echo` | 818 |
| `cd` | 806 |
| `cat` | 804 |
| `crontab` | 801 |
| `lscpu` | 801 |
| `ls` | 720 |
| `top` | 719 |
| `df` | 718 |
| `free` | 718 |
| `whoami` | 717 |
| `w` | 716 |
| `INFO` | 264 |
| `canary_env` | 191 |
| `PING` | 182 |


_Generated from first-party honeypot capture. CC BY 4.0._
