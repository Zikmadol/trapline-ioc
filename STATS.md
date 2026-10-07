# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1835 attackers** · **381,606 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 130 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 125 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 753 |
| `ssh-bruteforce` | 447 |
| `redis-exploit` | 344 |
| `mcp-abuse` | 118 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 11 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1234 |
| `redis` | 354 |
| `mcp` | 167 |
| `llamacpp` | 106 |
| `jupyter` | 62 |
| `vllm` | 62 |
| `litellm` | 58 |
| `hfhub` | 50 |
| `docker` | 41 |
| `ollama` | 36 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 717 |
| `345gs5662d34` | 603 |
| `admin` | 391 |
| `ubuntu` | 177 |
| `user` | 91 |
| `test` | 89 |
| `ftpuser` | 79 |
| `administrator` | 77 |
| `AdminGPON` | 56 |
| `admin1` | 54 |
| `Asalem` | 51 |
| `deploy` | 50 |
| `admin2` | 50 |
| `postgres` | 49 |
| `git` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 603 |
| `345gs5662d34` | 602 |
| `123456` | 437 |
| `123` | 262 |
| `1234` | 220 |
| `admin` | 143 |
| `12345678` | 142 |
| `12345` | 120 |
| `1` | 115 |
| `password` | 100 |
| `000000` | 87 |
| `123456789` | 76 |
| `admin123` | 76 |
| `P@ssw0rd` | 75 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 820 |
| `echo` | 706 |
| `lscpu` | 692 |
| `crontab` | 691 |
| `cd` | 690 |
| `cat` | 688 |
| `ls` | 621 |
| `top` | 620 |
| `df` | 619 |
| `free` | 619 |
| `whoami` | 618 |
| `w` | 617 |
| `INFO` | 228 |
| `PING` | 153 |
| `canary_env` | 148 |


_Generated from first-party honeypot capture. CC BY 4.0._
