# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1748 attackers** · **370,985 hostile actions** · covering 24 day(s) through 2026-10-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 121 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 119 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 732 |
| `ssh-bruteforce` | 421 |
| `redis-exploit` | 324 |
| `mcp-abuse` | 112 |
| `llamacpp-abuse` | 36 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 5 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1184 |
| `redis` | 334 |
| `mcp` | 159 |
| `llamacpp` | 101 |
| `vllm` | 59 |
| `jupyter` | 54 |
| `litellm` | 54 |
| `hfhub` | 49 |
| `ollama` | 36 |
| `docker` | 36 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 698 |
| `345gs5662d34` | 586 |
| `admin` | 372 |
| `ubuntu` | 172 |
| `user` | 87 |
| `test` | 86 |
| `administrator` | 78 |
| `ftpuser` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 56 |
| `a` | 52 |
| `admin2` | 52 |
| `Asalem` | 51 |
| `git` | 49 |
| `Caps` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 586 |
| `345gs5662d34` | 585 |
| `123456` | 425 |
| `123` | 246 |
| `1234` | 211 |
| `12345678` | 135 |
| `admin` | 131 |
| `1` | 112 |
| `12345` | 110 |
| `password` | 97 |
| `000000` | 84 |
| `P@ssw0rd` | 74 |
| `123456789` | 71 |
| `!QAZ2wsx` | 69 |
| `admin123` | 64 |

### Top commands run

| command | times |
|---|---|
| `uname` | 787 |
| `echo` | 684 |
| `lscpu` | 670 |
| `crontab` | 669 |
| `cd` | 667 |
| `cat` | 666 |
| `ls` | 604 |
| `top` | 603 |
| `df` | 602 |
| `free` | 602 |
| `whoami` | 601 |
| `w` | 600 |
| `INFO` | 216 |
| `PING` | 142 |
| `canary_env` | 141 |


_Generated from first-party honeypot capture. CC BY 4.0._
