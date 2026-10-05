# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1703 attackers** · **364,735 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 118 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 119 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 716 |
| `ssh-bruteforce` | 410 |
| `redis-exploit` | 315 |
| `mcp-abuse` | 108 |
| `llamacpp-abuse` | 32 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1157 |
| `redis` | 324 |
| `mcp` | 152 |
| `llamacpp` | 96 |
| `vllm` | 58 |
| `litellm` | 53 |
| `jupyter` | 52 |
| `hfhub` | 47 |
| `docker` | 36 |
| `ollama` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 686 |
| `345gs5662d34` | 573 |
| `admin` | 364 |
| `ubuntu` | 166 |
| `test` | 86 |
| `user` | 82 |
| `administrator` | 79 |
| `ftpuser` | 72 |
| `admin1` | 57 |
| `AdminGPON` | 56 |
| `a` | 53 |
| `admin2` | 53 |
| `Asalem` | 52 |
| `Caps` | 51 |
| `git` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 573 |
| `345gs5662d34` | 572 |
| `123456` | 410 |
| `123` | 237 |
| `1234` | 207 |
| `12345678` | 131 |
| `admin` | 128 |
| `1` | 110 |
| `12345` | 108 |
| `password` | 95 |
| `000000` | 83 |
| `123456789` | 70 |
| `P@ssw0rd` | 70 |
| `!QAZ2wsx` | 68 |
| `0` | 63 |

### Top commands run

| command | times |
|---|---|
| `uname` | 767 |
| `echo` | 668 |
| `lscpu` | 655 |
| `crontab` | 654 |
| `cd` | 650 |
| `cat` | 650 |
| `ls` | 592 |
| `top` | 591 |
| `df` | 590 |
| `free` | 590 |
| `whoami` | 589 |
| `w` | 588 |
| `INFO` | 209 |
| `canary_env` | 136 |
| `PING` | 135 |


_Generated from first-party honeypot capture. CC BY 4.0._
