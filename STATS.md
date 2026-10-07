# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1876 attackers** · **385,669 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 131 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 130 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 770 |
| `ssh-bruteforce` | 452 |
| `redis-exploit` | 351 |
| `mcp-abuse` | 126 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1258 |
| `redis` | 362 |
| `mcp` | 177 |
| `llamacpp` | 108 |
| `jupyter` | 64 |
| `vllm` | 64 |
| `litellm` | 58 |
| `hfhub` | 51 |
| `docker` | 41 |
| `ollama` | 38 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 729 |
| `345gs5662d34` | 619 |
| `admin` | 397 |
| `ubuntu` | 184 |
| `user` | 94 |
| `test` | 92 |
| `ftpuser` | 81 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 54 |
| `deploy` | 51 |
| `Asalem` | 51 |
| `postgres` | 50 |
| `git` | 50 |
| `Caps` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 619 |
| `345gs5662d34` | 618 |
| `123456` | 443 |
| `123` | 269 |
| `1234` | 224 |
| `admin` | 144 |
| `12345678` | 144 |
| `12345` | 124 |
| `1` | 121 |
| `password` | 103 |
| `000000` | 87 |
| `admin123` | 80 |
| `P@ssw0rd` | 79 |
| `123456789` | 78 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 840 |
| `echo` | 722 |
| `lscpu` | 708 |
| `cd` | 708 |
| `crontab` | 707 |
| `cat` | 706 |
| `ls` | 637 |
| `top` | 636 |
| `df` | 635 |
| `free` | 635 |
| `whoami` | 634 |
| `w` | 633 |
| `INFO` | 235 |
| `canary_env` | 157 |
| `PING` | 156 |


_Generated from first-party honeypot capture. CC BY 4.0._
