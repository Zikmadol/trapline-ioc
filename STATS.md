# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1919 attackers** · **391,918 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 134 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 132 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 789 |
| `ssh-bruteforce` | 461 |
| `redis-exploit` | 358 |
| `mcp-abuse` | 129 |
| `llamacpp-abuse` | 41 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 8 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1287 |
| `redis` | 369 |
| `mcp` | 181 |
| `llamacpp` | 112 |
| `vllm` | 66 |
| `jupyter` | 65 |
| `litellm` | 58 |
| `hfhub` | 51 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 742 |
| `345gs5662d34` | 635 |
| `admin` | 414 |
| `ubuntu` | 189 |
| `user` | 101 |
| `test` | 93 |
| `ftpuser` | 85 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `deploy` | 52 |
| `debian` | 51 |
| `git` | 51 |
| `postgres` | 50 |
| `Asalem` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 635 |
| `345gs5662d34` | 634 |
| `123456` | 458 |
| `123` | 279 |
| `1234` | 229 |
| `admin` | 149 |
| `12345678` | 148 |
| `12345` | 127 |
| `1` | 123 |
| `password` | 103 |
| `000000` | 88 |
| `P@ssw0rd` | 83 |
| `123456789` | 82 |
| `admin123` | 82 |
| `!QAZ2wsx` | 72 |

### Top commands run

| command | times |
|---|---|
| `uname` | 862 |
| `echo` | 740 |
| `cd` | 728 |
| `cat` | 726 |
| `lscpu` | 725 |
| `crontab` | 724 |
| `ls` | 652 |
| `top` | 651 |
| `df` | 650 |
| `free` | 650 |
| `whoami` | 649 |
| `w` | 648 |
| `INFO` | 240 |
| `canary_env` | 161 |
| `PING` | 158 |


_Generated from first-party honeypot capture. CC BY 4.0._
