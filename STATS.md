# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1130 attackers** · **246,698 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 66 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 68 |
| Stage-2 hosts named in payloads | 20 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 457 |
| `ssh-bruteforce` | 269 |
| `redis-exploit` | 230 |
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
| `ssh` | 745 |
| `redis` | 238 |
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
| `root` | 418 |
| `345gs5662d34` | 362 |
| `admin` | 226 |
| `administrator` | 69 |
| `ubuntu` | 68 |
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
| `3245gs5662d34` | 362 |
| `345gs5662d34` | 362 |
| `123456` | 195 |
| `123` | 123 |
| `1234` | 100 |
| `admin` | 73 |
| `12345678` | 61 |
| `000000` | 56 |
| `12345` | 53 |
| `!QAZ2wsx` | 49 |
| `password` | 48 |
| `1` | 48 |
| `0` | 47 |
| `0000` | 46 |
| `!Q2w3e4r` | 45 |

### Top commands run

| command | times |
|---|---|
| `uname` | 467 |
| `echo` | 416 |
| `lscpu` | 408 |
| `crontab` | 405 |
| `cd` | 404 |
| `cat` | 404 |
| `top` | 375 |
| `ls` | 374 |
| `df` | 374 |
| `free` | 374 |
| `whoami` | 373 |
| `w` | 372 |
| `INFO` | 156 |
| `canary_env` | 95 |
| `PING` | 92 |


_Generated from first-party honeypot capture. CC BY 4.0._
