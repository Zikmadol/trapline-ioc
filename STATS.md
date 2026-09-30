# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1268 attackers** · **284,572 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 78 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 85 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 534 |
| `ssh-bruteforce` | 300 |
| `redis-exploit` | 248 |
| `mcp-abuse` | 80 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 17 |
| `docker-abuse` | 13 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 855 |
| `redis` | 256 |
| `mcp` | 114 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 38 |
| `hfhub` | 35 |
| `litellm` | 35 |
| `docker` | 28 |
| `ollama` | 18 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 501 |
| `345gs5662d34` | 430 |
| `admin` | 256 |
| `ubuntu` | 103 |
| `administrator` | 78 |
| `admin1` | 64 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `user` | 49 |
| `admin123` | 49 |
| `Asalem` | 48 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 432 |
| `345gs5662d34` | 430 |
| `123456` | 250 |
| `123` | 144 |
| `1234` | 123 |
| `admin` | 81 |
| `12345678` | 77 |
| `password` | 67 |
| `000000` | 66 |
| `12345` | 60 |
| `1` | 59 |
| `!QAZ2wsx` | 55 |
| `0` | 53 |
| `0000` | 52 |
| `!Q2w3e4r` | 51 |

### Top commands run

| command | times |
|---|---|
| `uname` | 552 |
| `echo` | 494 |
| `lscpu` | 484 |
| `crontab` | 481 |
| `cd` | 479 |
| `cat` | 478 |
| `top` | 445 |
| `ls` | 444 |
| `df` | 444 |
| `free` | 444 |
| `whoami` | 443 |
| `w` | 442 |
| `INFO` | 165 |
| `canary_env` | 100 |
| `PING` | 99 |


_Generated from first-party honeypot capture. CC BY 4.0._
