# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1605 attackers** · **347,597 hostile actions** · covering 22 day(s) through 2026-10-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 114 |
| Stage-2 hosts named in payloads | 27 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 675 |
| `ssh-bruteforce` | 380 |
| `redis-exploit` | 307 |
| `mcp-abuse` | 103 |
| `llamacpp-abuse` | 28 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `llamacpp-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1086 |
| `redis` | 316 |
| `mcp` | 145 |
| `llamacpp` | 91 |
| `vllm` | 57 |
| `jupyter` | 50 |
| `litellm` | 50 |
| `hfhub` | 45 |
| `docker` | 35 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 646 |
| `345gs5662d34` | 545 |
| `admin` | 337 |
| `ubuntu` | 152 |
| `administrator` | 81 |
| `user` | 76 |
| `test` | 73 |
| `ftpuser` | 68 |
| `admin1` | 60 |
| `AdminGPON` | 55 |
| `a` | 53 |
| `Asalem` | 51 |
| `aaa` | 51 |
| `admin2` | 51 |
| `adminuser` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 546 |
| `345gs5662d34` | 544 |
| `123456` | 378 |
| `123` | 226 |
| `1234` | 191 |
| `admin` | 117 |
| `12345678` | 116 |
| `1` | 102 |
| `12345` | 94 |
| `password` | 90 |
| `000000` | 78 |
| `123456789` | 66 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `P@ssw0rd` | 61 |

### Top commands run

| command | times |
|---|---|
| `uname` | 715 |
| `echo` | 631 |
| `lscpu` | 618 |
| `crontab` | 617 |
| `cat` | 610 |
| `cd` | 609 |
| `ls` | 563 |
| `top` | 562 |
| `df` | 561 |
| `free` | 561 |
| `whoami` | 560 |
| `w` | 559 |
| `INFO` | 203 |
| `PING` | 132 |
| `canary_env` | 130 |


_Generated from first-party honeypot capture. CC BY 4.0._
