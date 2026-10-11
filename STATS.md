# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2203 attackers** · **448,138 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 150 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 153 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 914 |
| `ssh-bruteforce` | 511 |
| `redis-exploit` | 410 |
| `mcp-abuse` | 164 |
| `llamacpp-abuse` | 46 |
| `litellm-key-replay` | 32 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 22 |
| `canary-aws-key` | 19 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1468 |
| `redis` | 422 |
| `mcp` | 227 |
| `llamacpp` | 129 |
| `vllm` | 83 |
| `jupyter` | 82 |
| `litellm` | 72 |
| `hfhub` | 67 |
| `docker` | 52 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 846 |
| `345gs5662d34` | 731 |
| `admin` | 482 |
| `ubuntu` | 228 |
| `user` | 120 |
| `ftpuser` | 109 |
| `test` | 108 |
| `administrator` | 77 |
| `git` | 73 |
| `postgres` | 71 |
| `guest` | 66 |
| `deploy` | 66 |
| `admin1` | 59 |
| `AdminGPON` | 57 |
| `oracle` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 730 |
| `3245gs5662d34` | 727 |
| `123456` | 551 |
| `123` | 350 |
| `1234` | 276 |
| `12345678` | 184 |
| `admin` | 178 |
| `12345` | 174 |
| `1` | 153 |
| `password` | 118 |
| `P@ssw0rd` | 109 |
| `admin123` | 103 |
| `000000` | 98 |
| `123456789` | 89 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 997 |
| `echo` | 856 |
| `cd` | 847 |
| `cat` | 846 |
| `crontab` | 838 |
| `lscpu` | 838 |
| `ls` | 752 |
| `free` | 751 |
| `top` | 751 |
| `df` | 750 |
| `whoami` | 749 |
| `w` | 748 |
| `INFO` | 273 |
| `canary_env` | 199 |
| `PING` | 188 |


_Generated from first-party honeypot capture. CC BY 4.0._
