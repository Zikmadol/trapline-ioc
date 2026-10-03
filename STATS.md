# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1491 attackers** · **335,192 hostile actions** · covering 21 day(s) through 2026-10-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 104 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 103 |
| Stage-2 hosts named in payloads | 24 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 632 |
| `ssh-bruteforce` | 353 |
| `redis-exploit` | 285 |
| `mcp-abuse` | 95 |
| `llamacpp-abuse` | 26 |
| `litellm-key-replay` | 24 |
| `docker-abuse` | 16 |
| `ollama-abuse` | 12 |
| `canary-aws-key` | 10 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1012 |
| `redis` | 293 |
| `mcp` | 134 |
| `llamacpp` | 83 |
| `vllm` | 52 |
| `jupyter` | 45 |
| `litellm` | 45 |
| `hfhub` | 41 |
| `docker` | 33 |
| `ollama` | 21 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 599 |
| `345gs5662d34` | 509 |
| `admin` | 308 |
| `ubuntu` | 136 |
| `administrator` | 84 |
| `test` | 69 |
| `user` | 63 |
| `admin1` | 63 |
| `ftpuser` | 57 |
| `AdminGPON` | 55 |
| `a` | 55 |
| `admin2` | 54 |
| `adminuser` | 54 |
| `aaa` | 53 |
| `ai` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 510 |
| `345gs5662d34` | 508 |
| `123456` | 335 |
| `123` | 201 |
| `1234` | 176 |
| `12345678` | 107 |
| `admin` | 102 |
| `password` | 80 |
| `12345` | 80 |
| `1` | 78 |
| `000000` | 76 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `123456789` | 61 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 668 |
| `echo` | 593 |
| `lscpu` | 580 |
| `crontab` | 579 |
| `cd` | 568 |
| `cat` | 568 |
| `ls` | 525 |
| `top` | 525 |
| `df` | 524 |
| `free` | 524 |
| `whoami` | 523 |
| `w` | 522 |
| `INFO` | 187 |
| `PING` | 121 |
| `canary_env` | 120 |


_Generated from first-party honeypot capture. CC BY 4.0._
