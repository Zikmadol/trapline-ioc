# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2413 attackers** · **472,714 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 162 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 974 |
| `canary-aws-key` | 792 |
| `ssh-bruteforce` | 556 |
| `redis-exploit` | 463 |
| `mcp-abuse` | 188 |
| `llamacpp-abuse` | 52 |
| `litellm-key-replay` | 36 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1582 |
| `redis` | 476 |
| `mcp` | 263 |
| `llamacpp` | 153 |
| `vllm` | 97 |
| `jupyter` | 93 |
| `litellm` | 87 |
| `hfhub` | 74 |
| `docker` | 65 |
| `ollama` | 47 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 908 |
| `345gs5662d34` | 775 |
| `admin` | 528 |
| `ubuntu` | 254 |
| `user` | 129 |
| `ftpuser` | 119 |
| `test` | 115 |
| `administrator` | 82 |
| `git` | 80 |
| `postgres` | 79 |
| `deploy` | 75 |
| `guest` | 74 |
| `oracle` | 62 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 774 |
| `3245gs5662d34` | 771 |
| `123456` | 608 |
| `123` | 384 |
| `1234` | 297 |
| `12345678` | 202 |
| `admin` | 191 |
| `12345` | 185 |
| `1` | 172 |
| `password` | 130 |
| `P@ssw0rd` | 125 |
| `admin123` | 119 |
| `123456789` | 100 |
| `000000` | 100 |
| `!QAZ2wsx` | 91 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1071 |
| `cd` | 911 |
| `cat` | 909 |
| `echo` | 909 |
| `crontab` | 890 |
| `lscpu` | 889 |
| `ls` | 797 |
| `free` | 796 |
| `top` | 795 |
| `df` | 794 |
| `w` | 793 |
| `whoami` | 793 |
| `INFO` | 309 |
| `canary_env` | 224 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
