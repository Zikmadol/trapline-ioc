# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1820 attackers** · **379,059 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 128 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 122 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 749 |
| `ssh-bruteforce` | 443 |
| `redis-exploit` | 341 |
| `mcp-abuse` | 117 |
| `llamacpp-abuse` | 37 |
| `litellm-key-replay` | 27 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 11 |
| `vllm-abuse` | 6 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1224 |
| `redis` | 351 |
| `mcp` | 165 |
| `llamacpp` | 104 |
| `jupyter` | 61 |
| `vllm` | 59 |
| `litellm` | 57 |
| `hfhub` | 50 |
| `docker` | 41 |
| `ollama` | 36 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 714 |
| `345gs5662d34` | 602 |
| `admin` | 386 |
| `ubuntu` | 176 |
| `user` | 91 |
| `test` | 88 |
| `ftpuser` | 78 |
| `administrator` | 77 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `Asalem` | 51 |
| `admin2` | 51 |
| `deploy` | 50 |
| `a` | 50 |
| `postgres` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 602 |
| `345gs5662d34` | 601 |
| `123456` | 433 |
| `123` | 259 |
| `1234` | 220 |
| `12345678` | 141 |
| `admin` | 140 |
| `12345` | 119 |
| `1` | 112 |
| `password` | 100 |
| `000000` | 85 |
| `123456789` | 74 |
| `P@ssw0rd` | 74 |
| `admin123` | 74 |
| `!QAZ2wsx` | 70 |

### Top commands run

| command | times |
|---|---|
| `uname` | 815 |
| `echo` | 704 |
| `lscpu` | 690 |
| `crontab` | 689 |
| `cd` | 687 |
| `cat` | 685 |
| `ls` | 620 |
| `top` | 619 |
| `df` | 618 |
| `free` | 618 |
| `whoami` | 617 |
| `w` | 616 |
| `INFO` | 226 |
| `PING` | 151 |
| `canary_env` | 146 |


_Generated from first-party honeypot capture. CC BY 4.0._
