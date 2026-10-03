# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1478 attackers** · **333,406 hostile actions** · covering 21 day(s) through 2026-10-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 103 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 103 |
| Stage-2 hosts named in payloads | 24 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 627 |
| `ssh-bruteforce` | 350 |
| `redis-exploit` | 283 |
| `mcp-abuse` | 93 |
| `llamacpp-abuse` | 26 |
| `litellm-key-replay` | 23 |
| `docker-abuse` | 16 |
| `ollama-abuse` | 12 |
| `canary-aws-key` | 10 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1004 |
| `redis` | 291 |
| `mcp` | 132 |
| `llamacpp` | 83 |
| `vllm` | 52 |
| `jupyter` | 45 |
| `litellm` | 44 |
| `hfhub` | 41 |
| `docker` | 33 |
| `ollama` | 21 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 591 |
| `345gs5662d34` | 504 |
| `admin` | 305 |
| `ubuntu` | 135 |
| `administrator` | 84 |
| `test` | 68 |
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
| `3245gs5662d34` | 505 |
| `345gs5662d34` | 503 |
| `123456` | 329 |
| `123` | 200 |
| `1234` | 172 |
| `12345678` | 104 |
| `admin` | 99 |
| `password` | 80 |
| `12345` | 79 |
| `1` | 77 |
| `000000` | 76 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `123456789` | 60 |
| `0000` | 57 |

### Top commands run

| command | times |
|---|---|
| `uname` | 661 |
| `echo` | 588 |
| `lscpu` | 575 |
| `crontab` | 574 |
| `cd` | 563 |
| `cat` | 563 |
| `ls` | 520 |
| `top` | 520 |
| `df` | 519 |
| `free` | 519 |
| `whoami` | 518 |
| `w` | 517 |
| `INFO` | 186 |
| `PING` | 120 |
| `canary_env` | 118 |


_Generated from first-party honeypot capture. CC BY 4.0._
