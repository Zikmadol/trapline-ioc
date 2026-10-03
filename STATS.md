# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1525 attackers** · **338,587 hostile actions** · covering 21 day(s) through 2026-10-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 106 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 110 |
| Stage-2 hosts named in payloads | 26 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 643 |
| `ssh-bruteforce` | 358 |
| `redis-exploit` | 292 |
| `mcp-abuse` | 97 |
| `llamacpp-abuse` | 28 |
| `litellm-key-replay` | 24 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1031 |
| `redis` | 300 |
| `mcp` | 138 |
| `llamacpp` | 88 |
| `vllm` | 55 |
| `jupyter` | 47 |
| `litellm` | 47 |
| `hfhub` | 42 |
| `docker` | 34 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 606 |
| `345gs5662d34` | 516 |
| `admin` | 315 |
| `ubuntu` | 141 |
| `administrator` | 84 |
| `test` | 70 |
| `user` | 63 |
| `admin1` | 63 |
| `ftpuser` | 60 |
| `AdminGPON` | 55 |
| `a` | 55 |
| `aaa` | 54 |
| `admin2` | 54 |
| `adminuser` | 54 |
| `ai` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 517 |
| `345gs5662d34` | 515 |
| `123456` | 342 |
| `123` | 206 |
| `1234` | 180 |
| `12345678` | 110 |
| `admin` | 106 |
| `12345` | 85 |
| `password` | 81 |
| `1` | 80 |
| `000000` | 76 |
| `123456789` | 63 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 679 |
| `echo` | 601 |
| `lscpu` | 588 |
| `crontab` | 587 |
| `cd` | 577 |
| `cat` | 577 |
| `ls` | 532 |
| `top` | 532 |
| `df` | 531 |
| `free` | 531 |
| `whoami` | 530 |
| `w` | 529 |
| `INFO` | 192 |
| `PING` | 126 |
| `canary_env` | 124 |


_Generated from first-party honeypot capture. CC BY 4.0._
