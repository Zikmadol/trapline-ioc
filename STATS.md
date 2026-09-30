# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1294 attackers** · **287,061 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 83 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 89 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 551 |
| `ssh-bruteforce` | 302 |
| `redis-exploit` | 253 |
| `mcp-abuse` | 80 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 19 |
| `docker-abuse` | 13 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 874 |
| `redis` | 261 |
| `mcp` | 116 |
| `llamacpp` | 72 |
| `vllm` | 44 |
| `jupyter` | 40 |
| `litellm` | 37 |
| `hfhub` | 35 |
| `docker` | 28 |
| `ollama` | 19 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 517 |
| `345gs5662d34` | 441 |
| `admin` | 265 |
| `ubuntu` | 110 |
| `administrator` | 82 |
| `admin1` | 64 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `user` | 53 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `admin123` | 50 |
| `test` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 443 |
| `345gs5662d34` | 441 |
| `123456` | 265 |
| `123` | 149 |
| `1234` | 132 |
| `admin` | 81 |
| `12345678` | 81 |
| `password` | 68 |
| `000000` | 68 |
| `12345` | 64 |
| `1` | 63 |
| `!QAZ2wsx` | 55 |
| `0` | 54 |
| `123456789` | 53 |
| `0000` | 53 |

### Top commands run

| command | times |
|---|---|
| `uname` | 569 |
| `echo` | 508 |
| `lscpu` | 498 |
| `crontab` | 495 |
| `cd` | 491 |
| `cat` | 490 |
| `top` | 456 |
| `ls` | 455 |
| `df` | 455 |
| `free` | 455 |
| `whoami` | 454 |
| `w` | 453 |
| `INFO` | 167 |
| `PING` | 102 |
| `canary_env` | 100 |


_Generated from first-party honeypot capture. CC BY 4.0._
