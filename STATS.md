# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1546 attackers** · **340,732 hostile actions** · covering 21 day(s) through 2026-10-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 109 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 110 |
| Stage-2 hosts named in payloads | 26 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 651 |
| `ssh-bruteforce` | 363 |
| `redis-exploit` | 297 |
| `mcp-abuse` | 99 |
| `llamacpp-abuse` | 28 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1044 |
| `redis` | 305 |
| `mcp` | 140 |
| `llamacpp` | 88 |
| `vllm` | 56 |
| `litellm` | 48 |
| `jupyter` | 47 |
| `hfhub` | 42 |
| `docker` | 34 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 618 |
| `345gs5662d34` | 523 |
| `admin` | 322 |
| `ubuntu` | 142 |
| `administrator` | 83 |
| `test` | 69 |
| `user` | 66 |
| `ftpuser` | 62 |
| `admin1` | 62 |
| `AdminGPON` | 55 |
| `a` | 54 |
| `aaa` | 53 |
| `admin2` | 53 |
| `adminuser` | 53 |
| `ai` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 524 |
| `345gs5662d34` | 522 |
| `123456` | 351 |
| `123` | 213 |
| `1234` | 183 |
| `12345678` | 111 |
| `admin` | 109 |
| `12345` | 85 |
| `1` | 84 |
| `password` | 81 |
| `000000` | 77 |
| `123456789` | 64 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 687 |
| `echo` | 608 |
| `lscpu` | 595 |
| `crontab` | 594 |
| `cd` | 584 |
| `cat` | 584 |
| `ls` | 539 |
| `top` | 539 |
| `df` | 538 |
| `free` | 538 |
| `whoami` | 537 |
| `w` | 536 |
| `INFO` | 195 |
| `PING` | 127 |
| `canary_env` | 126 |


_Generated from first-party honeypot capture. CC BY 4.0._
