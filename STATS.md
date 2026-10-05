# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1654 attackers** · **357,089 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 114 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 115 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 696 |
| `ssh-bruteforce` | 392 |
| `redis-exploit` | 310 |
| `mcp-abuse` | 104 |
| `llamacpp-abuse` | 30 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `litellm-abuse` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1119 |
| `redis` | 319 |
| `mcp` | 146 |
| `llamacpp` | 94 |
| `vllm` | 57 |
| `litellm` | 52 |
| `jupyter` | 51 |
| `hfhub` | 46 |
| `ollama` | 35 |
| `docker` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 658 |
| `345gs5662d34` | 554 |
| `admin` | 354 |
| `ubuntu` | 155 |
| `administrator` | 81 |
| `user` | 78 |
| `test` | 74 |
| `ftpuser` | 70 |
| `admin1` | 60 |
| `AdminGPON` | 56 |
| `a` | 55 |
| `Asalem` | 52 |
| `Caps` | 51 |
| `aaa` | 51 |
| `admin2` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 555 |
| `345gs5662d34` | 553 |
| `123456` | 392 |
| `123` | 230 |
| `1234` | 197 |
| `12345678` | 124 |
| `admin` | 123 |
| `1` | 105 |
| `12345` | 96 |
| `password` | 93 |
| `000000` | 81 |
| `123456789` | 67 |
| `P@ssw0rd` | 67 |
| `!QAZ2wsx` | 67 |
| `0` | 63 |

### Top commands run

| command | times |
|---|---|
| `uname` | 739 |
| `echo` | 644 |
| `lscpu` | 631 |
| `crontab` | 630 |
| `cd` | 628 |
| `cat` | 628 |
| `ls` | 572 |
| `top` | 571 |
| `df` | 570 |
| `free` | 570 |
| `whoami` | 569 |
| `w` | 568 |
| `INFO` | 204 |
| `PING` | 133 |
| `canary_env` | 132 |


_Generated from first-party honeypot capture. CC BY 4.0._
