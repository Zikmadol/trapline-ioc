# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1243 attackers** · **278,687 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 78 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 81 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 518 |
| `ssh-bruteforce` | 297 |
| `redis-exploit` | 247 |
| `mcp-abuse` | 78 |
| `llamacpp-abuse` | 22 |
| `litellm-key-replay` | 17 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 835 |
| `redis` | 255 |
| `mcp` | 112 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 38 |
| `hfhub` | 35 |
| `litellm` | 33 |
| `docker` | 27 |
| `ollama` | 18 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 484 |
| `345gs5662d34` | 415 |
| `admin` | 250 |
| `ubuntu` | 98 |
| `administrator` | 77 |
| `admin1` | 64 |
| `admin2` | 54 |
| `ai` | 54 |
| `a` | 53 |
| `AdminGPON` | 51 |
| `aaa` | 51 |
| `adminuser` | 50 |
| `admin123` | 49 |
| `user` | 47 |
| `Asalem` | 47 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 416 |
| `345gs5662d34` | 415 |
| `123456` | 240 |
| `123` | 135 |
| `1234` | 120 |
| `admin` | 78 |
| `12345678` | 74 |
| `000000` | 65 |
| `password` | 62 |
| `12345` | 61 |
| `1` | 59 |
| `!QAZ2wsx` | 54 |
| `0` | 53 |
| `0000` | 51 |
| `!Q2w3e4r` | 50 |

### Top commands run

| command | times |
|---|---|
| `uname` | 536 |
| `echo` | 478 |
| `lscpu` | 468 |
| `crontab` | 465 |
| `cd` | 463 |
| `cat` | 462 |
| `top` | 429 |
| `ls` | 428 |
| `df` | 428 |
| `free` | 428 |
| `whoami` | 427 |
| `w` | 426 |
| `INFO` | 165 |
| `PING` | 99 |
| `canary_env` | 97 |


_Generated from first-party honeypot capture. CC BY 4.0._
