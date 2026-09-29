# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1187 attackers** · **264,314 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 74 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 76 |
| Stage-2 hosts named in payloads | 21 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 490 |
| `ssh-bruteforce` | 285 |
| `redis-exploit` | 235 |
| `mcp-abuse` | 76 |
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
| `ssh` | 795 |
| `redis` | 243 |
| `mcp` | 108 |
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
| `root` | 457 |
| `345gs5662d34` | 387 |
| `admin` | 239 |
| `ubuntu` | 80 |
| `administrator` | 75 |
| `admin1` | 58 |
| `a` | 51 |
| `admin2` | 50 |
| `ai` | 50 |
| `AdminGPON` | 49 |
| `aaa` | 49 |
| `adminuser` | 48 |
| `admin123` | 46 |
| `Asalem` | 45 |
| `Caps` | 45 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 387 |
| `345gs5662d34` | 387 |
| `123456` | 219 |
| `123` | 130 |
| `1234` | 106 |
| `admin` | 76 |
| `12345678` | 65 |
| `password` | 60 |
| `000000` | 60 |
| `1` | 57 |
| `12345` | 56 |
| `!QAZ2wsx` | 52 |
| `0` | 50 |
| `0000` | 49 |
| `!Q2w3e4r` | 48 |

### Top commands run

| command | times |
|---|---|
| `uname` | 501 |
| `echo` | 446 |
| `lscpu` | 437 |
| `crontab` | 434 |
| `cat` | 431 |
| `cd` | 430 |
| `top` | 401 |
| `ls` | 400 |
| `df` | 400 |
| `free` | 400 |
| `whoami` | 399 |
| `w` | 398 |
| `INFO` | 158 |
| `canary_env` | 95 |
| `PING` | 93 |


_Generated from first-party honeypot capture. CC BY 4.0._
