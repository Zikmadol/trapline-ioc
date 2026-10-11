# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2182 attackers** · **436,799 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 148 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 153 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 899 |
| `ssh-bruteforce` | 505 |
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
| `ssh` | 1447 |
| `redis` | 422 |
| `mcp` | 227 |
| `llamacpp` | 129 |
| `jupyter` | 82 |
| `vllm` | 82 |
| `litellm` | 72 |
| `hfhub` | 67 |
| `docker` | 52 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 834 |
| `345gs5662d34` | 718 |
| `admin` | 476 |
| `ubuntu` | 226 |
| `user` | 112 |
| `ftpuser` | 107 |
| `test` | 106 |
| `administrator` | 76 |
| `git` | 73 |
| `postgres` | 68 |
| `guest` | 65 |
| `deploy` | 63 |
| `admin1` | 58 |
| `oracle` | 57 |
| `AdminGPON` | 56 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 717 |
| `3245gs5662d34` | 716 |
| `123456` | 537 |
| `123` | 341 |
| `1234` | 272 |
| `12345678` | 179 |
| `admin` | 177 |
| `12345` | 172 |
| `1` | 151 |
| `password` | 115 |
| `P@ssw0rd` | 106 |
| `admin123` | 102 |
| `000000` | 96 |
| `123456789` | 89 |
| `!QAZ2wsx` | 84 |

### Top commands run

| command | times |
|---|---|
| `uname` | 981 |
| `echo` | 841 |
| `cd` | 833 |
| `cat` | 832 |
| `crontab` | 823 |
| `lscpu` | 823 |
| `ls` | 739 |
| `free` | 738 |
| `top` | 738 |
| `df` | 737 |
| `whoami` | 736 |
| `w` | 735 |
| `INFO` | 273 |
| `canary_env` | 199 |
| `PING` | 188 |


_Generated from first-party honeypot capture. CC BY 4.0._
