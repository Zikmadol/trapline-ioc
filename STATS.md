# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1958 attackers** · **395,768 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 136 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 134 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 811 |
| `ssh-bruteforce` | 464 |
| `redis-exploit` | 364 |
| `mcp-abuse` | 134 |
| `llamacpp-abuse` | 42 |
| `litellm-key-replay` | 29 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 9 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1313 |
| `redis` | 375 |
| `mcp` | 188 |
| `llamacpp` | 115 |
| `vllm` | 68 |
| `jupyter` | 67 |
| `litellm` | 60 |
| `hfhub` | 53 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 761 |
| `345gs5662d34` | 653 |
| `admin` | 424 |
| `ubuntu` | 194 |
| `user` | 101 |
| `test` | 98 |
| `ftpuser` | 87 |
| `administrator` | 76 |
| `admin1` | 57 |
| `AdminGPON` | 56 |
| `git` | 56 |
| `postgres` | 54 |
| `deploy` | 52 |
| `debian` | 51 |
| `guest` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 652 |
| `345gs5662d34` | 652 |
| `123456` | 473 |
| `123` | 289 |
| `1234` | 236 |
| `12345678` | 154 |
| `admin` | 152 |
| `12345` | 134 |
| `1` | 126 |
| `password` | 107 |
| `P@ssw0rd` | 89 |
| `000000` | 88 |
| `123456789` | 83 |
| `admin123` | 82 |
| `!QAZ2wsx` | 72 |

### Top commands run

| command | times |
|---|---|
| `uname` | 882 |
| `echo` | 761 |
| `cd` | 748 |
| `cat` | 746 |
| `lscpu` | 745 |
| `crontab` | 744 |
| `ls` | 671 |
| `top` | 670 |
| `df` | 669 |
| `free` | 669 |
| `whoami` | 668 |
| `w` | 667 |
| `INFO` | 243 |
| `canary_env` | 168 |
| `PING` | 163 |


_Generated from first-party honeypot capture. CC BY 4.0._
