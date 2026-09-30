# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1277 attackers** · **285,099 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 79 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 86 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 540 |
| `ssh-bruteforce` | 301 |
| `redis-exploit` | 250 |
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
| `ssh` | 862 |
| `redis` | 258 |
| `mcp` | 114 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 39 |
| `hfhub` | 35 |
| `litellm` | 35 |
| `docker` | 28 |
| `ollama` | 18 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 507 |
| `345gs5662d34` | 435 |
| `admin` | 259 |
| `ubuntu` | 106 |
| `administrator` | 78 |
| `admin1` | 64 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `user` | 50 |
| `admin123` | 49 |
| `Asalem` | 48 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 437 |
| `345gs5662d34` | 435 |
| `123456` | 256 |
| `123` | 144 |
| `1234` | 127 |
| `admin` | 81 |
| `12345678` | 77 |
| `password` | 67 |
| `000000` | 67 |
| `1` | 60 |
| `12345` | 60 |
| `!QAZ2wsx` | 55 |
| `0` | 53 |
| `0000` | 52 |
| `!Q2w3e4r` | 51 |

### Top commands run

| command | times |
|---|---|
| `uname` | 558 |
| `echo` | 499 |
| `lscpu` | 489 |
| `crontab` | 486 |
| `cd` | 484 |
| `cat` | 483 |
| `top` | 450 |
| `ls` | 449 |
| `df` | 449 |
| `free` | 449 |
| `whoami` | 448 |
| `w` | 447 |
| `INFO` | 166 |
| `canary_env` | 100 |
| `PING` | 100 |


_Generated from first-party honeypot capture. CC BY 4.0._
