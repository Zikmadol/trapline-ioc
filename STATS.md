# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1103 attackers** · **242,948 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 65 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 67 |
| Stage-2 hosts named in payloads | 20 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 440 |
| `ssh-bruteforce` | 263 |
| `redis-exploit` | 227 |
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
| `ssh` | 722 |
| `redis` | 235 |
| `mcp` | 107 |
| `llamacpp` | 66 |
| `vllm` | 42 |
| `jupyter` | 37 |
| `hfhub` | 34 |
| `litellm` | 30 |
| `docker` | 22 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 404 |
| `345gs5662d34` | 348 |
| `admin` | 222 |
| `administrator` | 68 |
| `ubuntu` | 66 |
| `admin1` | 53 |
| `AdminGPON` | 46 |
| `aaa` | 45 |
| `admin2` | 45 |
| `adminuser` | 45 |
| `a` | 44 |
| `ai` | 44 |
| `Asalem` | 42 |
| `Caps` | 42 |
| `admin123` | 42 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 348 |
| `345gs5662d34` | 348 |
| `123456` | 193 |
| `123` | 121 |
| `1234` | 99 |
| `admin` | 70 |
| `12345678` | 61 |
| `000000` | 54 |
| `!QAZ2wsx` | 49 |
| `12345` | 48 |
| `1` | 47 |
| `0` | 47 |
| `0000` | 46 |
| `!Q2w3e4r` | 45 |
| `password` | 43 |

### Top commands run

| command | times |
|---|---|
| `uname` | 449 |
| `echo` | 402 |
| `lscpu` | 394 |
| `crontab` | 391 |
| `cd` | 386 |
| `cat` | 386 |
| `top` | 361 |
| `ls` | 360 |
| `df` | 360 |
| `free` | 360 |
| `whoami` | 359 |
| `w` | 358 |
| `INFO` | 154 |
| `canary_env` | 95 |
| `PING` | 90 |


_Generated from first-party honeypot capture. CC BY 4.0._
