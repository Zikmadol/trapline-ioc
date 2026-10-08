# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1948 attackers** · **395,135 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 136 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 134 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 802 |
| `ssh-bruteforce` | 465 |
| `redis-exploit` | 364 |
| `mcp-abuse` | 133 |
| `llamacpp-abuse` | 41 |
| `litellm-key-replay` | 29 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 9 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1305 |
| `redis` | 375 |
| `mcp` | 187 |
| `llamacpp` | 114 |
| `vllm` | 68 |
| `jupyter` | 67 |
| `litellm` | 60 |
| `hfhub` | 53 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 755 |
| `345gs5662d34` | 646 |
| `admin` | 421 |
| `ubuntu` | 193 |
| `user` | 101 |
| `test` | 97 |
| `ftpuser` | 86 |
| `administrator` | 76 |
| `admin1` | 57 |
| `AdminGPON` | 56 |
| `git` | 55 |
| `postgres` | 53 |
| `deploy` | 52 |
| `debian` | 51 |
| `guest` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 646 |
| `345gs5662d34` | 645 |
| `123456` | 467 |
| `123` | 286 |
| `1234` | 236 |
| `12345678` | 153 |
| `admin` | 152 |
| `12345` | 133 |
| `1` | 126 |
| `password` | 105 |
| `000000` | 88 |
| `P@ssw0rd` | 84 |
| `123456789` | 83 |
| `admin123` | 82 |
| `!QAZ2wsx` | 72 |

### Top commands run

| command | times |
|---|---|
| `uname` | 874 |
| `echo` | 753 |
| `cd` | 740 |
| `cat` | 738 |
| `lscpu` | 737 |
| `crontab` | 736 |
| `ls` | 663 |
| `top` | 662 |
| `df` | 661 |
| `free` | 661 |
| `whoami` | 660 |
| `w` | 659 |
| `INFO` | 243 |
| `canary_env` | 166 |
| `PING` | 163 |


_Generated from first-party honeypot capture. CC BY 4.0._
