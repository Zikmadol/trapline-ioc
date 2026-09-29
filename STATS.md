# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1182 attackers** · **263,043 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 74 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 76 |
| Stage-2 hosts named in payloads | 21 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 484 |
| `ssh-bruteforce` | 286 |
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
| `ssh` | 790 |
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
| `root` | 454 |
| `345gs5662d34` | 382 |
| `admin` | 233 |
| `ubuntu` | 75 |
| `administrator` | 74 |
| `admin1` | 58 |
| `admin2` | 50 |
| `ai` | 50 |
| `AdminGPON` | 49 |
| `a` | 49 |
| `aaa` | 49 |
| `adminuser` | 48 |
| `admin123` | 46 |
| `Caps` | 45 |
| `adm1n` | 45 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 382 |
| `3245gs5662d34` | 381 |
| `123456` | 213 |
| `123` | 128 |
| `1234` | 105 |
| `admin` | 75 |
| `12345678` | 65 |
| `000000` | 60 |
| `password` | 57 |
| `12345` | 56 |
| `1` | 54 |
| `!QAZ2wsx` | 52 |
| `0` | 50 |
| `0000` | 49 |
| `!Q2w3e4r` | 48 |

### Top commands run

| command | times |
|---|---|
| `uname` | 496 |
| `echo` | 440 |
| `lscpu` | 432 |
| `crontab` | 428 |
| `cat` | 426 |
| `cd` | 425 |
| `top` | 396 |
| `df` | 395 |
| `ls` | 394 |
| `free` | 394 |
| `whoami` | 394 |
| `w` | 392 |
| `INFO` | 158 |
| `canary_env` | 95 |
| `PING` | 93 |


_Generated from first-party honeypot capture. CC BY 4.0._
