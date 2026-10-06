# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1786 attackers** · **374,159 hostile actions** · covering 24 day(s) through 2026-10-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 126 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 121 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 739 |
| `ssh-bruteforce` | 436 |
| `redis-exploit` | 337 |
| `mcp-abuse` | 114 |
| `llamacpp-abuse` | 36 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 6 |
| `vllm-abuse` | 6 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1207 |
| `redis` | 347 |
| `mcp` | 162 |
| `llamacpp` | 103 |
| `vllm` | 59 |
| `jupyter` | 56 |
| `litellm` | 55 |
| `hfhub` | 49 |
| `docker` | 40 |
| `ollama` | 36 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 708 |
| `345gs5662d34` | 591 |
| `admin` | 380 |
| `ubuntu` | 176 |
| `user` | 90 |
| `test` | 87 |
| `administrator` | 78 |
| `ftpuser` | 77 |
| `AdminGPON` | 56 |
| `admin1` | 56 |
| `a` | 52 |
| `admin2` | 52 |
| `Asalem` | 51 |
| `postgres` | 50 |
| `git` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 591 |
| `345gs5662d34` | 590 |
| `123456` | 430 |
| `123` | 253 |
| `1234` | 216 |
| `admin` | 138 |
| `12345678` | 138 |
| `12345` | 113 |
| `1` | 112 |
| `password` | 98 |
| `000000` | 85 |
| `P@ssw0rd` | 74 |
| `123456789` | 72 |
| `!QAZ2wsx` | 70 |
| `123123` | 66 |

### Top commands run

| command | times |
|---|---|
| `uname` | 800 |
| `echo` | 692 |
| `lscpu` | 678 |
| `crontab` | 677 |
| `cd` | 675 |
| `cat` | 673 |
| `ls` | 609 |
| `top` | 608 |
| `df` | 607 |
| `free` | 607 |
| `whoami` | 606 |
| `w` | 605 |
| `INFO` | 226 |
| `PING` | 149 |
| `canary_env` | 143 |


_Generated from first-party honeypot capture. CC BY 4.0._
