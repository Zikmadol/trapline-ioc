# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1930 attackers** · **393,807 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 135 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 134 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 796 |
| `ssh-bruteforce` | 460 |
| `redis-exploit` | 361 |
| `mcp-abuse` | 131 |
| `llamacpp-abuse` | 41 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 8 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1294 |
| `redis` | 372 |
| `mcp` | 184 |
| `llamacpp` | 113 |
| `vllm` | 66 |
| `jupyter` | 65 |
| `litellm` | 59 |
| `hfhub` | 53 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 746 |
| `345gs5662d34` | 640 |
| `admin` | 418 |
| `ubuntu` | 190 |
| `user` | 100 |
| `test` | 96 |
| `ftpuser` | 85 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `git` | 54 |
| `deploy` | 52 |
| `debian` | 51 |
| `guest` | 50 |
| `postgres` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 640 |
| `345gs5662d34` | 639 |
| `123456` | 461 |
| `123` | 284 |
| `1234` | 233 |
| `admin` | 150 |
| `12345678` | 149 |
| `12345` | 133 |
| `1` | 124 |
| `password` | 105 |
| `000000` | 88 |
| `123456789` | 83 |
| `P@ssw0rd` | 83 |
| `admin123` | 82 |
| `!QAZ2wsx` | 72 |

### Top commands run

| command | times |
|---|---|
| `uname` | 869 |
| `echo` | 747 |
| `cd` | 734 |
| `lscpu` | 732 |
| `cat` | 732 |
| `crontab` | 731 |
| `ls` | 658 |
| `top` | 657 |
| `df` | 656 |
| `free` | 656 |
| `whoami` | 655 |
| `w` | 654 |
| `INFO` | 242 |
| `canary_env` | 163 |
| `PING` | 161 |


_Generated from first-party honeypot capture. CC BY 4.0._
