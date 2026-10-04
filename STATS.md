# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1557 attackers** · **342,314 hostile actions** · covering 22 day(s) through 2026-10-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 111 |
| Stage-2 hosts named in payloads | 26 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 658 |
| `ssh-bruteforce` | 364 |
| `redis-exploit` | 297 |
| `mcp-abuse` | 100 |
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
| `ssh` | 1052 |
| `redis` | 306 |
| `mcp` | 142 |
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
| `345gs5662d34` | 529 |
| `admin` | 325 |
| `ubuntu` | 144 |
| `administrator` | 82 |
| `test` | 72 |
| `user` | 68 |
| `ftpuser` | 64 |
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
| `3245gs5662d34` | 530 |
| `345gs5662d34` | 528 |
| `123456` | 357 |
| `123` | 216 |
| `1234` | 186 |
| `12345678` | 113 |
| `admin` | 110 |
| `1` | 86 |
| `12345` | 86 |
| `password` | 84 |
| `000000` | 77 |
| `123456789` | 64 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 694 |
| `echo` | 615 |
| `lscpu` | 602 |
| `crontab` | 601 |
| `cd` | 591 |
| `cat` | 591 |
| `ls` | 546 |
| `top` | 546 |
| `df` | 545 |
| `free` | 545 |
| `whoami` | 544 |
| `w` | 543 |
| `INFO` | 196 |
| `canary_env` | 127 |
| `PING` | 127 |


_Generated from first-party honeypot capture. CC BY 4.0._
