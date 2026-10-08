# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1933 attackers** · **394,107 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 135 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 134 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 797 |
| `ssh-bruteforce` | 462 |
| `redis-exploit` | 361 |
| `mcp-abuse` | 131 |
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
| `ssh` | 1297 |
| `redis` | 372 |
| `mcp` | 184 |
| `llamacpp` | 113 |
| `jupyter` | 67 |
| `vllm` | 66 |
| `litellm` | 59 |
| `hfhub` | 53 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 748 |
| `345gs5662d34` | 641 |
| `admin` | 419 |
| `ubuntu` | 191 |
| `user` | 100 |
| `test` | 97 |
| `ftpuser` | 86 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `git` | 54 |
| `deploy` | 52 |
| `debian` | 51 |
| `guest` | 50 |
| `postgres` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 641 |
| `345gs5662d34` | 640 |
| `123456` | 462 |
| `123` | 285 |
| `1234` | 234 |
| `admin` | 150 |
| `12345678` | 149 |
| `12345` | 133 |
| `1` | 125 |
| `password` | 105 |
| `000000` | 88 |
| `123456789` | 83 |
| `P@ssw0rd` | 83 |
| `admin123` | 82 |
| `!QAZ2wsx` | 72 |

### Top commands run

| command | times |
|---|---|
| `uname` | 870 |
| `echo` | 748 |
| `cd` | 735 |
| `lscpu` | 733 |
| `cat` | 733 |
| `crontab` | 732 |
| `ls` | 659 |
| `top` | 658 |
| `df` | 657 |
| `free` | 657 |
| `whoami` | 656 |
| `w` | 655 |
| `INFO` | 242 |
| `canary_env` | 163 |
| `PING` | 161 |


_Generated from first-party honeypot capture. CC BY 4.0._
