# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1121 attackers** · **246,266 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 66 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 67 |
| Stage-2 hosts named in payloads | 20 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 451 |
| `ssh-bruteforce` | 268 |
| `redis-exploit` | 228 |
| `mcp-abuse` | 76 |
| `llamacpp-abuse` | 21 |
| `litellm-key-replay` | 16 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 738 |
| `redis` | 236 |
| `mcp` | 107 |
| `llamacpp` | 66 |
| `vllm` | 42 |
| `jupyter` | 37 |
| `hfhub` | 34 |
| `litellm` | 32 |
| `docker` | 22 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 414 |
| `345gs5662d34` | 359 |
| `admin` | 224 |
| `administrator` | 69 |
| `ubuntu` | 67 |
| `admin1` | 54 |
| `ai` | 47 |
| `AdminGPON` | 46 |
| `aaa` | 46 |
| `a` | 45 |
| `admin2` | 45 |
| `adminuser` | 45 |
| `admin123` | 43 |
| `Asalem` | 42 |
| `Caps` | 42 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 359 |
| `345gs5662d34` | 359 |
| `123456` | 195 |
| `123` | 122 |
| `1234` | 100 |
| `admin` | 72 |
| `12345678` | 61 |
| `000000` | 55 |
| `12345` | 53 |
| `!QAZ2wsx` | 49 |
| `1` | 48 |
| `0` | 47 |
| `0000` | 46 |
| `password` | 45 |
| `!Q2w3e4r` | 45 |

### Top commands run

| command | times |
|---|---|
| `uname` | 461 |
| `echo` | 412 |
| `lscpu` | 404 |
| `crontab` | 401 |
| `cd` | 398 |
| `cat` | 398 |
| `top` | 371 |
| `ls` | 370 |
| `df` | 370 |
| `free` | 370 |
| `whoami` | 369 |
| `w` | 368 |
| `INFO` | 155 |
| `canary_env` | 95 |
| `PING` | 90 |


_Generated from first-party honeypot capture. CC BY 4.0._
