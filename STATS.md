# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1759 attackers** · **372,020 hostile actions** · covering 24 day(s) through 2026-10-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 123 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 121 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 733 |
| `ssh-bruteforce` | 424 |
| `redis-exploit` | 330 |
| `mcp-abuse` | 113 |
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
| `ssh` | 1189 |
| `redis` | 340 |
| `mcp` | 161 |
| `llamacpp` | 102 |
| `vllm` | 59 |
| `jupyter` | 55 |
| `litellm` | 54 |
| `hfhub` | 49 |
| `docker` | 37 |
| `ollama` | 36 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 699 |
| `345gs5662d34` | 587 |
| `admin` | 373 |
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
| `3245gs5662d34` | 587 |
| `345gs5662d34` | 586 |
| `123456` | 428 |
| `123` | 247 |
| `1234` | 211 |
| `12345678` | 135 |
| `admin` | 133 |
| `1` | 112 |
| `12345` | 112 |
| `password` | 96 |
| `000000` | 84 |
| `P@ssw0rd` | 74 |
| `123456789` | 71 |
| `!QAZ2wsx` | 70 |
| `0` | 65 |

### Top commands run

| command | times |
|---|---|
| `uname` | 790 |
| `echo` | 686 |
| `lscpu` | 672 |
| `crontab` | 671 |
| `cd` | 668 |
| `cat` | 667 |
| `ls` | 605 |
| `top` | 604 |
| `df` | 603 |
| `free` | 603 |
| `whoami` | 602 |
| `w` | 601 |
| `INFO` | 221 |
| `PING` | 145 |
| `canary_env` | 142 |


_Generated from first-party honeypot capture. CC BY 4.0._
