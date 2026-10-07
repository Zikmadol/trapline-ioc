# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1842 attackers** · **382,012 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 130 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 125 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 759 |
| `ssh-bruteforce` | 447 |
| `redis-exploit` | 344 |
| `mcp-abuse` | 118 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 11 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1240 |
| `redis` | 354 |
| `mcp` | 167 |
| `llamacpp` | 106 |
| `jupyter` | 62 |
| `vllm` | 62 |
| `litellm` | 58 |
| `hfhub` | 50 |
| `docker` | 41 |
| `ollama` | 37 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 720 |
| `345gs5662d34` | 607 |
| `admin` | 393 |
| `ubuntu` | 178 |
| `user` | 92 |
| `test` | 90 |
| `ftpuser` | 79 |
| `administrator` | 77 |
| `AdminGPON` | 56 |
| `admin1` | 54 |
| `deploy` | 51 |
| `Asalem` | 51 |
| `admin2` | 50 |
| `postgres` | 49 |
| `git` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 607 |
| `345gs5662d34` | 606 |
| `123456` | 438 |
| `123` | 263 |
| `1234` | 221 |
| `admin` | 143 |
| `12345678` | 142 |
| `12345` | 122 |
| `1` | 118 |
| `password` | 101 |
| `000000` | 87 |
| `admin123` | 77 |
| `123456789` | 76 |
| `P@ssw0rd` | 75 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 826 |
| `echo` | 710 |
| `lscpu` | 696 |
| `cd` | 696 |
| `crontab` | 695 |
| `cat` | 694 |
| `ls` | 625 |
| `top` | 624 |
| `df` | 623 |
| `free` | 623 |
| `whoami` | 622 |
| `w` | 621 |
| `INFO` | 228 |
| `PING` | 153 |
| `canary_env` | 148 |


_Generated from first-party honeypot capture. CC BY 4.0._
