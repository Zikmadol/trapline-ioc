# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1553 attackers** · **342,129 hostile actions** · covering 22 day(s) through 2026-10-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 111 |
| Stage-2 hosts named in payloads | 26 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 657 |
| `ssh-bruteforce` | 363 |
| `redis-exploit` | 296 |
| `mcp-abuse` | 99 |
| `llamacpp-abuse` | 28 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1050 |
| `redis` | 305 |
| `mcp` | 141 |
| `llamacpp` | 89 |
| `vllm` | 56 |
| `jupyter` | 48 |
| `litellm` | 48 |
| `hfhub` | 43 |
| `docker` | 34 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 624 |
| `345gs5662d34` | 528 |
| `admin` | 325 |
| `ubuntu` | 143 |
| `administrator` | 82 |
| `test` | 72 |
| `user` | 68 |
| `ftpuser` | 63 |
| `admin1` | 61 |
| `AdminGPON` | 55 |
| `a` | 54 |
| `aaa` | 52 |
| `admin2` | 52 |
| `adminuser` | 52 |
| `Asalem` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 529 |
| `345gs5662d34` | 527 |
| `123456` | 357 |
| `123` | 215 |
| `1234` | 186 |
| `12345678` | 112 |
| `admin` | 110 |
| `1` | 86 |
| `12345` | 86 |
| `password` | 83 |
| `000000` | 77 |
| `123456789` | 64 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 693 |
| `echo` | 614 |
| `lscpu` | 601 |
| `crontab` | 600 |
| `cd` | 590 |
| `cat` | 590 |
| `ls` | 545 |
| `top` | 545 |
| `df` | 544 |
| `free` | 544 |
| `whoami` | 543 |
| `w` | 542 |
| `INFO` | 195 |
| `PING` | 127 |
| `canary_env` | 126 |


_Generated from first-party honeypot capture. CC BY 4.0._
