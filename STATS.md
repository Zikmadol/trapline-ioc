# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1664 attackers** · **358,897 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 114 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 116 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 700 |
| `ssh-bruteforce` | 396 |
| `redis-exploit` | 311 |
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
| `ssh` | 1127 |
| `redis` | 320 |
| `mcp` | 146 |
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
| `root` | 665 |
| `345gs5662d34` | 557 |
| `admin` | 357 |
| `ubuntu` | 158 |
| `test` | 82 |
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
| `3245gs5662d34` | 558 |
| `345gs5662d34` | 556 |
| `123456` | 395 |
| `123` | 232 |
| `1234` | 201 |
| `12345678` | 130 |
| `admin` | 124 |
| `1` | 106 |
| `12345` | 96 |
| `password` | 94 |
| `000000` | 82 |
| `P@ssw0rd` | 68 |
| `123456789` | 67 |
| `!QAZ2wsx` | 67 |
| `0` | 63 |

### Top commands run

| command | times |
|---|---|
| `uname` | 743 |
| `echo` | 648 |
| `lscpu` | 635 |
| `crontab` | 634 |
| `cd` | 632 |
| `cat` | 632 |
| `ls` | 576 |
| `top` | 575 |
| `df` | 574 |
| `free` | 574 |
| `whoami` | 573 |
| `w` | 572 |
| `INFO` | 205 |
| `PING` | 133 |
| `canary_env` | 132 |


_Generated from first-party honeypot capture. CC BY 4.0._
