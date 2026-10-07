# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1822 attackers** · **380,265 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 129 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 123 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 750 |
| `ssh-bruteforce` | 442 |
| `redis-exploit` | 341 |
| `mcp-abuse` | 118 |
| `llamacpp-abuse` | 38 |
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
| `ssh` | 1225 |
| `redis` | 351 |
| `mcp` | 166 |
| `llamacpp` | 105 |
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
| `root` | 715 |
| `345gs5662d34` | 603 |
| `admin` | 386 |
| `ubuntu` | 176 |
| `user` | 91 |
| `test` | 88 |
| `ftpuser` | 78 |
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
| `123456` | 434 |
| `123` | 260 |
| `1234` | 219 |
| `12345678` | 141 |
| `admin` | 140 |
| `12345` | 119 |
| `1` | 113 |
| `password` | 100 |
| `000000` | 86 |
| `123456789` | 75 |
| `P@ssw0rd` | 74 |
| `admin123` | 74 |
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
