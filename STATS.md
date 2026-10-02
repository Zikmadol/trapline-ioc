# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1452 attackers** · **329,723 hostile actions** · covering 20 day(s) through 2026-10-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 101 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 101 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 612 |
| `ssh-bruteforce` | 348 |
| `redis-exploit` | 278 |
| `mcp-abuse` | 92 |
| `llamacpp-abuse` | 26 |
| `litellm-key-replay` | 23 |
| `docker-abuse` | 14 |
| `ollama-abuse` | 12 |
| `canary-aws-key` | 10 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 987 |
| `redis` | 286 |
| `mcp` | 131 |
| `llamacpp` | 82 |
| `vllm` | 51 |
| `jupyter` | 45 |
| `litellm` | 44 |
| `hfhub` | 41 |
| `docker` | 31 |
| `ollama` | 21 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 581 |
| `345gs5662d34` | 493 |
| `admin` | 300 |
| `ubuntu` | 137 |
| `administrator` | 84 |
| `test` | 65 |
| `user` | 63 |
| `admin1` | 63 |
| `AdminGPON` | 55 |
| `a` | 54 |
| `admin2` | 54 |
| `adminuser` | 54 |
| `ftpuser` | 53 |
| `ai` | 53 |
| `aaa` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 495 |
| `345gs5662d34` | 492 |
| `123456` | 321 |
| `123` | 193 |
| `1234` | 164 |
| `12345678` | 103 |
| `admin` | 95 |
| `password` | 78 |
| `1` | 76 |
| `000000` | 76 |
| `12345` | 74 |
| `!QAZ2wsx` | 63 |
| `0` | 61 |
| `123456789` | 58 |
| `0000` | 57 |

### Top commands run

| command | times |
|---|---|
| `uname` | 645 |
| `echo` | 574 |
| `lscpu` | 561 |
| `crontab` | 560 |
| `cat` | 551 |
| `cd` | 550 |
| `ls` | 508 |
| `top` | 508 |
| `df` | 507 |
| `free` | 507 |
| `whoami` | 506 |
| `w` | 505 |
| `INFO` | 182 |
| `canary_env` | 117 |
| `PING` | 117 |


_Generated from first-party honeypot capture. CC BY 4.0._
