# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1505 attackers** · **336,916 hostile actions** · covering 21 day(s) through 2026-10-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 105 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 104 |
| Stage-2 hosts named in payloads | 25 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 639 |
| `ssh-bruteforce` | 357 |
| `redis-exploit` | 286 |
| `mcp-abuse` | 95 |
| `llamacpp-abuse` | 27 |
| `litellm-key-replay` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `ollama-abuse` | 12 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1023 |
| `redis` | 294 |
| `mcp` | 134 |
| `llamacpp` | 85 |
| `vllm` | 52 |
| `jupyter` | 45 |
| `litellm` | 45 |
| `hfhub` | 41 |
| `docker` | 33 |
| `ollama` | 21 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 605 |
| `345gs5662d34` | 514 |
| `admin` | 312 |
| `ubuntu` | 137 |
| `administrator` | 84 |
| `test` | 69 |
| `user` | 63 |
| `admin1` | 63 |
| `ftpuser` | 59 |
| `AdminGPON` | 55 |
| `a` | 55 |
| `admin2` | 54 |
| `adminuser` | 54 |
| `aaa` | 53 |
| `ai` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 515 |
| `345gs5662d34` | 513 |
| `123456` | 340 |
| `123` | 202 |
| `1234` | 178 |
| `12345678` | 108 |
| `admin` | 104 |
| `12345` | 84 |
| `password` | 80 |
| `1` | 79 |
| `000000` | 76 |
| `!QAZ2wsx` | 63 |
| `123456789` | 62 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 675 |
| `echo` | 598 |
| `lscpu` | 585 |
| `crontab` | 584 |
| `cd` | 574 |
| `cat` | 574 |
| `ls` | 530 |
| `top` | 530 |
| `df` | 529 |
| `free` | 529 |
| `whoami` | 528 |
| `w` | 527 |
| `INFO` | 187 |
| `canary_env` | 121 |
| `PING` | 121 |


_Generated from first-party honeypot capture. CC BY 4.0._
