# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1940 attackers** · **394,689 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 136 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 134 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 801 |
| `ssh-bruteforce` | 462 |
| `redis-exploit` | 363 |
| `mcp-abuse` | 132 |
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
| `ssh` | 1301 |
| `redis` | 374 |
| `mcp` | 186 |
| `llamacpp` | 114 |
| `jupyter` | 67 |
| `vllm` | 67 |
| `litellm` | 59 |
| `hfhub` | 53 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 751 |
| `345gs5662d34` | 644 |
| `admin` | 420 |
| `ubuntu` | 192 |
| `user` | 101 |
| `test` | 97 |
| `ftpuser` | 86 |
| `administrator` | 76 |
| `admin1` | 57 |
| `AdminGPON` | 56 |
| `git` | 54 |
| `deploy` | 52 |
| `debian` | 51 |
| `guest` | 50 |
| `postgres` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 644 |
| `345gs5662d34` | 643 |
| `123456` | 463 |
| `123` | 286 |
| `1234` | 234 |
| `admin` | 150 |
| `12345678` | 150 |
| `12345` | 133 |
| `1` | 126 |
| `password` | 105 |
| `000000` | 88 |
| `123456789` | 83 |
| `P@ssw0rd` | 83 |
| `admin123` | 82 |
| `!QAZ2wsx` | 72 |

### Top commands run

| command | times |
|---|---|
| `uname` | 873 |
| `echo` | 751 |
| `cd` | 738 |
| `lscpu` | 736 |
| `cat` | 736 |
| `crontab` | 735 |
| `ls` | 662 |
| `top` | 661 |
| `df` | 660 |
| `free` | 660 |
| `whoami` | 659 |
| `w` | 658 |
| `INFO` | 243 |
| `canary_env` | 164 |
| `PING` | 163 |


_Generated from first-party honeypot capture. CC BY 4.0._
