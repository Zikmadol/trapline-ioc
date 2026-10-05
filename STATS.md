# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1668 attackers** · **359,645 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 115 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 117 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 701 |
| `ssh-bruteforce` | 398 |
| `redis-exploit` | 312 |
| `mcp-abuse` | 104 |
| `llamacpp-abuse` | 30 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1130 |
| `redis` | 321 |
| `mcp` | 147 |
| `llamacpp` | 94 |
| `vllm` | 58 |
| `jupyter` | 52 |
| `litellm` | 52 |
| `hfhub` | 46 |
| `docker` | 36 |
| `ollama` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 666 |
| `345gs5662d34` | 558 |
| `admin` | 358 |
| `ubuntu` | 158 |
| `test` | 83 |
| `administrator` | 81 |
| `user` | 79 |
| `ftpuser` | 71 |
| `admin1` | 59 |
| `AdminGPON` | 56 |
| `a` | 55 |
| `Asalem` | 52 |
| `Caps` | 51 |
| `aaa` | 50 |
| `admin2` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 559 |
| `345gs5662d34` | 557 |
| `123456` | 396 |
| `123` | 233 |
| `1234` | 202 |
| `12345678` | 130 |
| `admin` | 124 |
| `1` | 106 |
| `12345` | 97 |
| `password` | 95 |
| `000000` | 83 |
| `P@ssw0rd` | 68 |
| `123456789` | 67 |
| `!QAZ2wsx` | 67 |
| `0` | 63 |

### Top commands run

| command | times |
|---|---|
| `uname` | 745 |
| `echo` | 650 |
| `lscpu` | 637 |
| `crontab` | 636 |
| `cd` | 633 |
| `cat` | 633 |
| `ls` | 577 |
| `top` | 576 |
| `df` | 575 |
| `free` | 575 |
| `whoami` | 574 |
| `w` | 573 |
| `INFO` | 206 |
| `PING` | 133 |
| `canary_env` | 132 |


_Generated from first-party honeypot capture. CC BY 4.0._
