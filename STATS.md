# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2053 attackers** · **416,132 hostile actions** · covering 27 day(s) through 2026-10-09

| signal | count |
|---|---|
| GPU / AI-hardware probing | 143 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 140 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 851 |
| `ssh-bruteforce` | 483 |
| `redis-exploit` | 380 |
| `mcp-abuse` | 145 |
| `llamacpp-abuse` | 42 |
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
| `ssh` | 1373 |
| `redis` | 392 |
| `mcp` | 202 |
| `llamacpp` | 118 |
| `jupyter` | 72 |
| `vllm` | 72 |
| `litellm` | 64 |
| `hfhub` | 57 |
| `docker` | 45 |
| `ollama` | 40 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 794 |
| `345gs5662d34` | 685 |
| `admin` | 444 |
| `ubuntu` | 211 |
| `user` | 105 |
| `test` | 104 |
| `ftpuser` | 93 |
| `administrator` | 75 |
| `git` | 65 |
| `postgres` | 60 |
| `deploy` | 59 |
| `AdminGPON` | 56 |
| `guest` | 55 |
| `admin1` | 55 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 685 |
| `345gs5662d34` | 684 |
| `123456` | 505 |
| `123` | 305 |
| `1234` | 256 |
| `12345678` | 166 |
| `admin` | 161 |
| `12345` | 154 |
| `1` | 143 |
| `password` | 115 |
| `P@ssw0rd` | 94 |
| `000000` | 93 |
| `admin123` | 89 |
| `123456789` | 85 |
| `!QAZ2wsx` | 80 |

### Top commands run

| command | times |
|---|---|
| `uname` | 926 |
| `echo` | 802 |
| `crontab` | 785 |
| `lscpu` | 785 |
| `cd` | 783 |
| `cat` | 781 |
| `ls` | 705 |
| `top` | 704 |
| `df` | 703 |
| `free` | 703 |
| `whoami` | 702 |
| `w` | 701 |
| `INFO` | 254 |
| `canary_env` | 179 |
| `PING` | 173 |


_Generated from first-party honeypot capture. CC BY 4.0._
