# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1111 attackers** · **245,727 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 65 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 67 |
| Stage-2 hosts named in payloads | 20 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 444 |
| `ssh-bruteforce` | 266 |
| `redis-exploit` | 228 |
| `mcp-abuse` | 76 |
| `llamacpp-abuse` | 21 |
| `litellm-key-replay` | 15 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 729 |
| `redis` | 236 |
| `mcp` | 107 |
| `llamacpp` | 66 |
| `vllm` | 42 |
| `jupyter` | 37 |
| `hfhub` | 34 |
| `litellm` | 31 |
| `docker` | 22 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 408 |
| `345gs5662d34` | 353 |
| `admin` | 223 |
| `administrator` | 68 |
| `ubuntu` | 66 |
| `admin1` | 53 |
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
| `3245gs5662d34` | 353 |
| `345gs5662d34` | 353 |
| `123456` | 193 |
| `123` | 120 |
| `1234` | 99 |
| `admin` | 72 |
| `12345678` | 61 |
| `000000` | 55 |
| `12345` | 51 |
| `!QAZ2wsx` | 49 |
| `0` | 47 |
| `1` | 46 |
| `0000` | 46 |
| `password` | 45 |
| `!Q2w3e4r` | 45 |

### Top commands run

| command | times |
|---|---|
| `uname` | 453 |
| `echo` | 406 |
| `lscpu` | 398 |
| `crontab` | 395 |
| `cd` | 391 |
| `cat` | 391 |
| `top` | 365 |
| `ls` | 364 |
| `df` | 364 |
| `free` | 364 |
| `whoami` | 363 |
| `w` | 362 |
| `INFO` | 155 |
| `canary_env` | 95 |
| `PING` | 90 |


_Generated from first-party honeypot capture. CC BY 4.0._
