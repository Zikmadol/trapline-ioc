# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1824 attackers** · **381,242 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 129 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 124 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 750 |
| `ssh-bruteforce` | 443 |
| `redis-exploit` | 341 |
| `mcp-abuse` | 118 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 11 |
| `vllm-abuse` | 6 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1226 |
| `redis` | 351 |
| `mcp` | 166 |
| `llamacpp` | 106 |
| `jupyter` | 61 |
| `vllm` | 61 |
| `litellm` | 58 |
| `hfhub` | 50 |
| `docker` | 41 |
| `ollama` | 36 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 715 |
| `345gs5662d34` | 603 |
| `admin` | 387 |
| `ubuntu` | 176 |
| `user` | 91 |
| `test` | 88 |
| `ftpuser` | 79 |
| `administrator` | 76 |
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
| `123456` | 435 |
| `123` | 260 |
| `1234` | 220 |
| `12345678` | 142 |
| `admin` | 141 |
| `12345` | 120 |
| `1` | 114 |
| `password` | 100 |
| `000000` | 87 |
| `123456789` | 75 |
| `P@ssw0rd` | 75 |
| `admin123` | 75 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 816 |
| `echo` | 706 |
| `lscpu` | 692 |
| `crontab` | 691 |
| `cd` | 688 |
| `cat` | 686 |
| `ls` | 621 |
| `top` | 620 |
| `df` | 619 |
| `free` | 619 |
| `whoami` | 618 |
| `w` | 617 |
| `INFO` | 226 |
| `PING` | 151 |
| `canary_env` | 148 |


_Generated from first-party honeypot capture. CC BY 4.0._
