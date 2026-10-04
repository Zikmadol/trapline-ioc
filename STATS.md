# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1616 attackers** · **348,220 hostile actions** · covering 22 day(s) through 2026-10-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 114 |
| Stage-2 hosts named in payloads | 27 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 682 |
| `ssh-bruteforce` | 382 |
| `redis-exploit` | 307 |
| `mcp-abuse` | 103 |
| `llamacpp-abuse` | 30 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `llamacpp-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1095 |
| `redis` | 316 |
| `mcp` | 145 |
| `llamacpp` | 93 |
| `vllm` | 57 |
| `jupyter` | 51 |
| `litellm` | 50 |
| `hfhub` | 46 |
| `docker` | 35 |
| `ollama` | 28 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 651 |
| `345gs5662d34` | 550 |
| `admin` | 341 |
| `ubuntu` | 152 |
| `administrator` | 81 |
| `user` | 77 |
| `test` | 73 |
| `ftpuser` | 68 |
| `admin1` | 60 |
| `AdminGPON` | 55 |
| `a` | 53 |
| `Asalem` | 51 |
| `aaa` | 51 |
| `admin2` | 51 |
| `adminuser` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 551 |
| `345gs5662d34` | 549 |
| `123456` | 380 |
| `123` | 226 |
| `1234` | 194 |
| `admin` | 119 |
| `12345678` | 119 |
| `1` | 102 |
| `12345` | 94 |
| `password` | 92 |
| `000000` | 79 |
| `123456789` | 66 |
| `P@ssw0rd` | 64 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |

### Top commands run

| command | times |
|---|---|
| `uname` | 722 |
| `echo` | 636 |
| `lscpu` | 623 |
| `crontab` | 622 |
| `cat` | 617 |
| `cd` | 616 |
| `ls` | 568 |
| `top` | 567 |
| `df` | 566 |
| `free` | 566 |
| `whoami` | 565 |
| `w` | 564 |
| `INFO` | 203 |
| `PING` | 132 |
| `canary_env` | 130 |


_Generated from first-party honeypot capture. CC BY 4.0._
