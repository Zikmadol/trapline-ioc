# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2139 attackers** · **431,802 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 145 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 150 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 886 |
| `ssh-bruteforce` | 495 |
| `redis-exploit` | 399 |
| `mcp-abuse` | 158 |
| `llamacpp-abuse` | 45 |
| `litellm-key-replay` | 32 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 22 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1424 |
| `redis` | 410 |
| `mcp` | 218 |
| `llamacpp` | 126 |
| `jupyter` | 78 |
| `vllm` | 78 |
| `litellm` | 69 |
| `hfhub` | 64 |
| `docker` | 52 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 819 |
| `345gs5662d34` | 706 |
| `admin` | 469 |
| `ubuntu` | 223 |
| `user` | 109 |
| `test` | 104 |
| `ftpuser` | 101 |
| `administrator` | 76 |
| `git` | 69 |
| `guest` | 64 |
| `postgres` | 62 |
| `deploy` | 62 |
| `AdminGPON` | 56 |
| `admin1` | 56 |
| `debian` | 54 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 705 |
| `345gs5662d34` | 705 |
| `123456` | 526 |
| `123` | 330 |
| `1234` | 267 |
| `12345678` | 176 |
| `admin` | 171 |
| `12345` | 166 |
| `1` | 150 |
| `password` | 114 |
| `P@ssw0rd` | 104 |
| `admin123` | 99 |
| `000000` | 96 |
| `123456789` | 89 |
| `!QAZ2wsx` | 82 |

### Top commands run

| command | times |
|---|---|
| `uname` | 964 |
| `echo` | 824 |
| `cd` | 820 |
| `cat` | 818 |
| `crontab` | 807 |
| `lscpu` | 807 |
| `ls` | 726 |
| `top` | 725 |
| `df` | 724 |
| `free` | 724 |
| `whoami` | 723 |
| `w` | 722 |
| `INFO` | 265 |
| `canary_env` | 192 |
| `PING` | 182 |


_Generated from first-party honeypot capture. CC BY 4.0._
