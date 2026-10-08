# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1925 attackers** · **392,847 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 134 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 132 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 795 |
| `ssh-bruteforce` | 459 |
| `redis-exploit` | 360 |
| `mcp-abuse` | 129 |
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
| `ssh` | 1291 |
| `redis` | 371 |
| `mcp` | 181 |
| `llamacpp` | 112 |
| `vllm` | 66 |
| `jupyter` | 65 |
| `litellm` | 59 |
| `hfhub` | 52 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 745 |
| `345gs5662d34` | 640 |
| `admin` | 417 |
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
| `postgres` | 50 |
| `Asalem` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 640 |
| `345gs5662d34` | 639 |
| `123456` | 461 |
| `123` | 284 |
| `1234` | 232 |
| `admin` | 150 |
| `12345678` | 149 |
| `12345` | 131 |
| `1` | 124 |
| `password` | 105 |
| `000000` | 88 |
| `P@ssw0rd` | 83 |
| `123456789` | 82 |
| `admin123` | 82 |
| `!QAZ2wsx` | 72 |

### Top commands run

| command | times |
|---|---|
| `uname` | 867 |
| `echo` | 745 |
| `cd` | 733 |
| `cat` | 731 |
| `lscpu` | 730 |
| `crontab` | 729 |
| `ls` | 657 |
| `top` | 656 |
| `df` | 655 |
| `free` | 655 |
| `whoami` | 654 |
| `w` | 653 |
| `INFO` | 241 |
| `canary_env` | 161 |
| `PING` | 160 |


_Generated from first-party honeypot capture. CC BY 4.0._
