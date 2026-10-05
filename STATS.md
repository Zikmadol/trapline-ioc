# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1680 attackers** · **361,667 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 116 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 118 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 704 |
| `ssh-bruteforce` | 405 |
| `redis-exploit` | 313 |
| `mcp-abuse` | 105 |
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
| `ssh` | 1140 |
| `redis` | 322 |
| `mcp` | 148 |
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
| `root` | 673 |
| `345gs5662d34` | 562 |
| `admin` | 363 |
| `ubuntu` | 161 |
| `test` | 83 |
| `administrator` | 81 |
| `user` | 80 |
| `ftpuser` | 72 |
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
| `3245gs5662d34` | 563 |
| `345gs5662d34` | 561 |
| `123456` | 402 |
| `123` | 233 |
| `1234` | 204 |
| `12345678` | 131 |
| `admin` | 127 |
| `1` | 108 |
| `12345` | 100 |
| `password` | 96 |
| `000000` | 83 |
| `P@ssw0rd` | 70 |
| `123456789` | 68 |
| `!QAZ2wsx` | 68 |
| `0` | 63 |

### Top commands run

| command | times |
|---|---|
| `uname` | 752 |
| `echo` | 655 |
| `lscpu` | 642 |
| `crontab` | 641 |
| `cd` | 637 |
| `cat` | 637 |
| `ls` | 581 |
| `top` | 580 |
| `df` | 579 |
| `free` | 579 |
| `whoami` | 578 |
| `w` | 577 |
| `INFO` | 207 |
| `canary_env` | 133 |
| `PING` | 133 |


_Generated from first-party honeypot capture. CC BY 4.0._
