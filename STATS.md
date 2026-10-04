# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1588 attackers** · **346,524 hostile actions** · covering 22 day(s) through 2026-10-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 112 |
| Stage-2 hosts named in payloads | 27 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 671 |
| `ssh-bruteforce` | 374 |
| `redis-exploit` | 301 |
| `mcp-abuse` | 102 |
| `llamacpp-abuse` | 28 |
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
| `ssh` | 1075 |
| `redis` | 310 |
| `mcp` | 144 |
| `llamacpp` | 91 |
| `vllm` | 57 |
| `jupyter` | 49 |
| `litellm` | 49 |
| `hfhub` | 44 |
| `docker` | 35 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 639 |
| `345gs5662d34` | 540 |
| `admin` | 331 |
| `ubuntu` | 148 |
| `administrator` | 81 |
| `user` | 75 |
| `test` | 73 |
| `ftpuser` | 67 |
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
| `3245gs5662d34` | 541 |
| `345gs5662d34` | 539 |
| `123456` | 372 |
| `123` | 225 |
| `1234` | 189 |
| `12345678` | 114 |
| `admin` | 113 |
| `1` | 99 |
| `12345` | 93 |
| `password` | 90 |
| `000000` | 77 |
| `123456789` | 65 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `P@ssw0rd` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 709 |
| `echo` | 626 |
| `lscpu` | 613 |
| `crontab` | 612 |
| `cat` | 605 |
| `cd` | 604 |
| `ls` | 558 |
| `top` | 557 |
| `df` | 556 |
| `free` | 556 |
| `whoami` | 555 |
| `w` | 554 |
| `INFO` | 199 |
| `canary_env` | 129 |
| `PING` | 128 |


_Generated from first-party honeypot capture. CC BY 4.0._
