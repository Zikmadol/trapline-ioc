# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1797 attackers** · **375,868 hostile actions** · covering 24 day(s) through 2026-10-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 126 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 121 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 741 |
| `ssh-bruteforce` | 438 |
| `redis-exploit` | 338 |
| `mcp-abuse` | 115 |
| `llamacpp-abuse` | 36 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 11 |
| `vllm-abuse` | 6 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1211 |
| `redis` | 348 |
| `mcp` | 163 |
| `llamacpp` | 103 |
| `jupyter` | 61 |
| `vllm` | 59 |
| `litellm` | 55 |
| `hfhub` | 49 |
| `docker` | 40 |
| `ollama` | 36 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 709 |
| `345gs5662d34` | 595 |
| `admin` | 382 |
| `ubuntu` | 176 |
| `user` | 90 |
| `test` | 87 |
| `ftpuser` | 78 |
| `administrator` | 77 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `Asalem` | 51 |
| `a` | 51 |
| `admin2` | 51 |
| `postgres` | 50 |
| `git` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 595 |
| `345gs5662d34` | 594 |
| `123456` | 431 |
| `123` | 254 |
| `1234` | 217 |
| `12345678` | 139 |
| `admin` | 138 |
| `12345` | 113 |
| `1` | 112 |
| `password` | 99 |
| `000000` | 85 |
| `P@ssw0rd` | 74 |
| `123456789` | 72 |
| `!QAZ2wsx` | 70 |
| `123123` | 67 |

### Top commands run

| command | times |
|---|---|
| `uname` | 804 |
| `echo` | 696 |
| `lscpu` | 682 |
| `crontab` | 681 |
| `cd` | 679 |
| `cat` | 677 |
| `ls` | 613 |
| `top` | 612 |
| `df` | 611 |
| `free` | 611 |
| `whoami` | 610 |
| `w` | 609 |
| `INFO` | 226 |
| `PING` | 150 |
| `canary_env` | 144 |


_Generated from first-party honeypot capture. CC BY 4.0._
