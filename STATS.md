# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1221 attackers** · **272,152 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 75 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 78 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 505 |
| `ssh-bruteforce` | 292 |
| `redis-exploit` | 244 |
| `mcp-abuse` | 78 |
| `llamacpp-abuse` | 22 |
| `litellm-key-replay` | 17 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 817 |
| `redis` | 252 |
| `mcp` | 112 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 38 |
| `hfhub` | 35 |
| `litellm` | 33 |
| `docker` | 25 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 474 |
| `345gs5662d34` | 401 |
| `admin` | 244 |
| `ubuntu` | 91 |
| `administrator` | 76 |
| `admin1` | 62 |
| `a` | 52 |
| `ai` | 52 |
| `admin2` | 51 |
| `AdminGPON` | 50 |
| `aaa` | 50 |
| `adminuser` | 49 |
| `admin123` | 47 |
| `Asalem` | 46 |
| `Caps` | 46 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 401 |
| `345gs5662d34` | 401 |
| `123456` | 227 |
| `123` | 133 |
| `1234` | 114 |
| `admin` | 77 |
| `12345678` | 71 |
| `000000` | 63 |
| `password` | 62 |
| `12345` | 60 |
| `1` | 57 |
| `!QAZ2wsx` | 53 |
| `0` | 51 |
| `0000` | 50 |
| `!Q2w3e4r` | 49 |

### Top commands run

| command | times |
|---|---|
| `uname` | 519 |
| `echo` | 462 |
| `lscpu` | 452 |
| `crontab` | 449 |
| `cd` | 448 |
| `cat` | 448 |
| `top` | 415 |
| `ls` | 414 |
| `df` | 414 |
| `free` | 414 |
| `whoami` | 413 |
| `w` | 412 |
| `INFO` | 163 |
| `canary_env` | 97 |
| `PING` | 97 |


_Generated from first-party honeypot capture. CC BY 4.0._
