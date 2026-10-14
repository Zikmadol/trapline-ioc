# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2388 attackers** · **469,458 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 160 |
| Used a planted canary credential | 16 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 967 |
| `canary-aws-key` | 699 |
| `ssh-bruteforce` | 550 |
| `redis-exploit` | 458 |
| `mcp-abuse` | 187 |
| `llamacpp-abuse` | 51 |
| `litellm-key-replay` | 35 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1569 |
| `redis` | 471 |
| `mcp` | 262 |
| `llamacpp` | 152 |
| `vllm` | 97 |
| `jupyter` | 93 |
| `litellm` | 85 |
| `hfhub` | 74 |
| `docker` | 65 |
| `ollama` | 46 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 901 |
| `345gs5662d34` | 769 |
| `admin` | 526 |
| `ubuntu` | 252 |
| `user` | 127 |
| `ftpuser` | 119 |
| `test` | 114 |
| `administrator` | 82 |
| `postgres` | 79 |
| `git` | 79 |
| `guest` | 73 |
| `deploy` | 72 |
| `oracle` | 61 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 768 |
| `3245gs5662d34` | 765 |
| `123456` | 602 |
| `123` | 381 |
| `1234` | 293 |
| `12345678` | 201 |
| `admin` | 190 |
| `12345` | 182 |
| `1` | 170 |
| `password` | 129 |
| `P@ssw0rd` | 123 |
| `admin123` | 116 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 90 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1060 |
| `cd` | 904 |
| `cat` | 902 |
| `echo` | 901 |
| `crontab` | 882 |
| `lscpu` | 881 |
| `ls` | 791 |
| `free` | 790 |
| `top` | 789 |
| `df` | 788 |
| `w` | 787 |
| `whoami` | 787 |
| `INFO` | 305 |
| `canary_env` | 223 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
