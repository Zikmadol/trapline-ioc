# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1686 attackers** · **361,945 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 116 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 118 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 706 |
| `ssh-bruteforce` | 406 |
| `redis-exploit` | 314 |
| `mcp-abuse` | 107 |
| `llamacpp-abuse` | 31 |
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
| `ssh` | 1143 |
| `redis` | 323 |
| `mcp` | 150 |
| `llamacpp` | 95 |
| `vllm` | 58 |
| `litellm` | 53 |
| `jupyter` | 52 |
| `hfhub` | 46 |
| `docker` | 36 |
| `ollama` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 676 |
| `345gs5662d34` | 564 |
| `admin` | 365 |
| `ubuntu` | 161 |
| `test` | 83 |
| `user` | 82 |
| `administrator` | 81 |
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
| `3245gs5662d34` | 565 |
| `345gs5662d34` | 563 |
| `123456` | 402 |
| `123` | 236 |
| `1234` | 204 |
| `12345678` | 131 |
| `admin` | 128 |
| `1` | 108 |
| `12345` | 102 |
| `password` | 98 |
| `000000` | 83 |
| `P@ssw0rd` | 70 |
| `123456789` | 68 |
| `!QAZ2wsx` | 68 |
| `0` | 63 |

### Top commands run

| command | times |
|---|---|
| `uname` | 754 |
| `echo` | 657 |
| `lscpu` | 644 |
| `crontab` | 643 |
| `cd` | 639 |
| `cat` | 639 |
| `ls` | 583 |
| `top` | 582 |
| `df` | 581 |
| `free` | 581 |
| `whoami` | 580 |
| `w` | 579 |
| `INFO` | 208 |
| `canary_env` | 135 |
| `PING` | 134 |


_Generated from first-party honeypot capture. CC BY 4.0._
