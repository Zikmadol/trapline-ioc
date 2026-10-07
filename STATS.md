# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1850 attackers** · **383,158 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 130 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 126 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 761 |
| `ssh-bruteforce` | 449 |
| `redis-exploit` | 346 |
| `mcp-abuse` | 120 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 11 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1244 |
| `redis` | 357 |
| `mcp` | 169 |
| `llamacpp` | 106 |
| `jupyter` | 62 |
| `vllm` | 62 |
| `litellm` | 58 |
| `hfhub` | 50 |
| `docker` | 41 |
| `ollama` | 37 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 721 |
| `345gs5662d34` | 610 |
| `admin` | 394 |
| `ubuntu` | 178 |
| `user` | 93 |
| `test` | 92 |
| `ftpuser` | 79 |
| `administrator` | 77 |
| `AdminGPON` | 56 |
| `admin1` | 54 |
| `deploy` | 51 |
| `Asalem` | 51 |
| `postgres` | 50 |
| `admin2` | 50 |
| `git` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 610 |
| `345gs5662d34` | 609 |
| `123456` | 439 |
| `123` | 264 |
| `1234` | 220 |
| `admin` | 143 |
| `12345678` | 143 |
| `12345` | 122 |
| `1` | 119 |
| `password` | 102 |
| `000000` | 87 |
| `123456789` | 77 |
| `admin123` | 77 |
| `P@ssw0rd` | 75 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 829 |
| `echo` | 713 |
| `lscpu` | 699 |
| `cd` | 699 |
| `crontab` | 698 |
| `cat` | 697 |
| `ls` | 628 |
| `top` | 627 |
| `df` | 626 |
| `free` | 626 |
| `whoami` | 625 |
| `w` | 624 |
| `INFO` | 230 |
| `PING` | 154 |
| `canary_env` | 150 |


_Generated from first-party honeypot capture. CC BY 4.0._
