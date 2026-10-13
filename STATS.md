# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2315 attackers** · **458,517 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 15 |
| Seen on more than one sensor | 165 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 939 |
| `ssh-bruteforce` | 537 |
| `redis-exploit` | 437 |
| `canary-aws-key` | 331 |
| `mcp-abuse` | 184 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 34 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1525 |
| `redis` | 450 |
| `mcp` | 254 |
| `llamacpp` | 140 |
| `jupyter` | 88 |
| `vllm` | 88 |
| `litellm` | 78 |
| `hfhub` | 71 |
| `docker` | 60 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 875 |
| `345gs5662d34` | 750 |
| `admin` | 504 |
| `ubuntu` | 247 |
| `user` | 122 |
| `ftpuser` | 115 |
| `test` | 111 |
| `administrator` | 79 |
| `git` | 78 |
| `postgres` | 77 |
| `guest` | 70 |
| `deploy` | 67 |
| `admin1` | 59 |
| `AdminGPON` | 57 |
| `oracle` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 749 |
| `3245gs5662d34` | 746 |
| `123456` | 575 |
| `123` | 365 |
| `1234` | 287 |
| `12345678` | 191 |
| `admin` | 184 |
| `12345` | 178 |
| `1` | 162 |
| `password` | 126 |
| `P@ssw0rd` | 117 |
| `admin123` | 109 |
| `000000` | 98 |
| `123456789` | 96 |
| `!QAZ2wsx` | 87 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1027 |
| `echo` | 877 |
| `cd` | 875 |
| `cat` | 874 |
| `crontab` | 858 |
| `lscpu` | 858 |
| `ls` | 771 |
| `free` | 770 |
| `top` | 770 |
| `df` | 769 |
| `whoami` | 768 |
| `w` | 767 |
| `INFO` | 294 |
| `canary_env` | 220 |
| `PING` | 196 |


_Generated from first-party honeypot capture. CC BY 4.0._
