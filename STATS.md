# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1199 attackers** · **265,090 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 74 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 76 |
| Stage-2 hosts named in payloads | 21 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 494 |
| `ssh-bruteforce` | 289 |
| `redis-exploit` | 238 |
| `mcp-abuse` | 77 |
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
| `ssh` | 803 |
| `redis` | 246 |
| `mcp` | 109 |
| `llamacpp` | 71 |
| `vllm` | 42 |
| `jupyter` | 38 |
| `hfhub` | 34 |
| `litellm` | 33 |
| `docker` | 24 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 462 |
| `345gs5662d34` | 391 |
| `admin` | 241 |
| `ubuntu` | 84 |
| `administrator` | 75 |
| `admin1` | 58 |
| `a` | 51 |
| `ai` | 51 |
| `admin2` | 50 |
| `AdminGPON` | 49 |
| `aaa` | 49 |
| `adminuser` | 48 |
| `admin123` | 46 |
| `Asalem` | 45 |
| `Caps` | 45 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 391 |
| `345gs5662d34` | 391 |
| `123456` | 222 |
| `123` | 132 |
| `1234` | 107 |
| `admin` | 76 |
| `12345678` | 66 |
| `password` | 62 |
| `000000` | 62 |
| `1` | 57 |
| `12345` | 57 |
| `!QAZ2wsx` | 52 |
| `0` | 50 |
| `0000` | 49 |
| `!Q2w3e4r` | 48 |

### Top commands run

| command | times |
|---|---|
| `uname` | 508 |
| `echo` | 450 |
| `lscpu` | 441 |
| `crontab` | 438 |
| `cat` | 438 |
| `cd` | 437 |
| `top` | 405 |
| `ls` | 404 |
| `df` | 404 |
| `free` | 404 |
| `whoami` | 403 |
| `w` | 402 |
| `INFO` | 161 |
| `canary_env` | 96 |
| `PING` | 94 |


_Generated from first-party honeypot capture. CC BY 4.0._
