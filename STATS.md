# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1903 attackers** · **389,824 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 133 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 132 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 784 |
| `ssh-bruteforce` | 454 |
| `redis-exploit` | 357 |
| `mcp-abuse` | 127 |
| `llamacpp-abuse` | 41 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1275 |
| `redis` | 368 |
| `mcp` | 179 |
| `llamacpp` | 112 |
| `jupyter` | 65 |
| `vllm` | 65 |
| `litellm` | 58 |
| `hfhub` | 51 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 735 |
| `345gs5662d34` | 627 |
| `admin` | 407 |
| `ubuntu` | 187 |
| `user` | 97 |
| `test` | 92 |
| `ftpuser` | 85 |
| `administrator` | 75 |
| `AdminGPON` | 56 |
| `admin1` | 54 |
| `git` | 51 |
| `deploy` | 51 |
| `Asalem` | 50 |
| `postgres` | 49 |
| `guest` | 48 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 627 |
| `345gs5662d34` | 626 |
| `123456` | 452 |
| `123` | 273 |
| `1234` | 228 |
| `12345678` | 147 |
| `admin` | 146 |
| `12345` | 125 |
| `1` | 123 |
| `password` | 102 |
| `000000` | 87 |
| `P@ssw0rd` | 82 |
| `admin123` | 82 |
| `123456789` | 79 |
| `!QAZ2wsx` | 72 |

### Top commands run

| command | times |
|---|---|
| `uname` | 853 |
| `echo` | 731 |
| `cd` | 720 |
| `cat` | 718 |
| `lscpu` | 717 |
| `crontab` | 716 |
| `ls` | 645 |
| `top` | 644 |
| `df` | 643 |
| `free` | 643 |
| `whoami` | 642 |
| `w` | 641 |
| `INFO` | 239 |
| `canary_env` | 159 |
| `PING` | 158 |


_Generated from first-party honeypot capture. CC BY 4.0._
