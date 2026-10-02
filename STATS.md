# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1450 attackers** · **328,951 hostile actions** · covering 20 day(s) through 2026-10-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 101 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 100 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 611 |
| `ssh-bruteforce` | 347 |
| `redis-exploit` | 277 |
| `mcp-abuse` | 92 |
| `llamacpp-abuse` | 26 |
| `litellm-key-replay` | 23 |
| `docker-abuse` | 15 |
| `ollama-abuse` | 12 |
| `canary-aws-key` | 10 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 986 |
| `redis` | 285 |
| `mcp` | 131 |
| `llamacpp` | 82 |
| `vllm` | 51 |
| `jupyter` | 44 |
| `litellm` | 44 |
| `hfhub` | 41 |
| `docker` | 31 |
| `ollama` | 21 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 582 |
| `345gs5662d34` | 491 |
| `admin` | 300 |
| `ubuntu` | 137 |
| `administrator` | 85 |
| `test` | 65 |
| `user` | 63 |
| `admin1` | 63 |
| `AdminGPON` | 55 |
| `ftpuser` | 54 |
| `a` | 54 |
| `admin2` | 54 |
| `adminuser` | 54 |
| `ai` | 53 |
| `aaa` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 493 |
| `345gs5662d34` | 490 |
| `123456` | 318 |
| `123` | 191 |
| `1234` | 164 |
| `12345678` | 100 |
| `admin` | 95 |
| `password` | 78 |
| `1` | 76 |
| `000000` | 75 |
| `12345` | 74 |
| `!QAZ2wsx` | 63 |
| `0` | 61 |
| `123456789` | 58 |
| `0000` | 57 |

### Top commands run

| command | times |
|---|---|
| `uname` | 643 |
| `echo` | 572 |
| `lscpu` | 559 |
| `crontab` | 558 |
| `cat` | 549 |
| `cd` | 548 |
| `ls` | 506 |
| `top` | 506 |
| `df` | 505 |
| `free` | 505 |
| `whoami` | 504 |
| `w` | 503 |
| `INFO` | 182 |
| `canary_env` | 117 |
| `PING` | 116 |


_Generated from first-party honeypot capture. CC BY 4.0._
