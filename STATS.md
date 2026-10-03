# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1547 attackers** · **341,076 hostile actions** · covering 21 day(s) through 2026-10-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 110 |
| Stage-2 hosts named in payloads | 26 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 652 |
| `ssh-bruteforce` | 363 |
| `redis-exploit` | 297 |
| `mcp-abuse` | 99 |
| `llamacpp-abuse` | 28 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1045 |
| `redis` | 305 |
| `mcp` | 140 |
| `llamacpp` | 88 |
| `vllm` | 56 |
| `litellm` | 48 |
| `jupyter` | 47 |
| `hfhub` | 42 |
| `docker` | 34 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 619 |
| `345gs5662d34` | 524 |
| `admin` | 322 |
| `ubuntu` | 143 |
| `administrator` | 83 |
| `test` | 69 |
| `user` | 67 |
| `ftpuser` | 62 |
| `admin1` | 62 |
| `AdminGPON` | 55 |
| `a` | 54 |
| `aaa` | 53 |
| `admin2` | 53 |
| `adminuser` | 53 |
| `ai` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 525 |
| `345gs5662d34` | 523 |
| `123456` | 352 |
| `123` | 214 |
| `1234` | 184 |
| `12345678` | 111 |
| `admin` | 110 |
| `12345` | 85 |
| `1` | 84 |
| `password` | 82 |
| `000000` | 77 |
| `123456789` | 64 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 688 |
| `echo` | 609 |
| `lscpu` | 596 |
| `crontab` | 595 |
| `cd` | 585 |
| `cat` | 585 |
| `ls` | 540 |
| `top` | 540 |
| `df` | 539 |
| `free` | 539 |
| `whoami` | 538 |
| `w` | 537 |
| `INFO` | 195 |
| `PING` | 127 |
| `canary_env` | 126 |


_Generated from first-party honeypot capture. CC BY 4.0._
