# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1771 attackers** · **372,511 hostile actions** · covering 24 day(s) through 2026-10-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 123 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 121 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 736 |
| `ssh-bruteforce` | 429 |
| `redis-exploit` | 333 |
| `mcp-abuse` | 113 |
| `llamacpp-abuse` | 36 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 6 |
| `vllm-abuse` | 6 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1197 |
| `redis` | 343 |
| `mcp` | 161 |
| `llamacpp` | 102 |
| `vllm` | 59 |
| `jupyter` | 56 |
| `litellm` | 55 |
| `hfhub` | 49 |
| `docker` | 38 |
| `ollama` | 36 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 704 |
| `345gs5662d34` | 590 |
| `admin` | 376 |
| `ubuntu` | 174 |
| `user` | 89 |
| `test` | 87 |
| `administrator` | 78 |
| `ftpuser` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 56 |
| `a` | 52 |
| `admin2` | 52 |
| `Asalem` | 51 |
| `postgres` | 49 |
| `git` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 590 |
| `345gs5662d34` | 589 |
| `123456` | 429 |
| `123` | 250 |
| `1234` | 213 |
| `12345678` | 137 |
| `admin` | 133 |
| `1` | 112 |
| `12345` | 112 |
| `password` | 97 |
| `000000` | 84 |
| `P@ssw0rd` | 74 |
| `123456789` | 72 |
| `!QAZ2wsx` | 70 |
| `123123` | 65 |

### Top commands run

| command | times |
|---|---|
| `uname` | 794 |
| `echo` | 689 |
| `lscpu` | 675 |
| `crontab` | 674 |
| `cd` | 672 |
| `cat` | 670 |
| `ls` | 608 |
| `top` | 607 |
| `df` | 606 |
| `free` | 606 |
| `whoami` | 605 |
| `w` | 604 |
| `INFO` | 224 |
| `PING` | 146 |
| `canary_env` | 142 |


_Generated from first-party honeypot capture. CC BY 4.0._
