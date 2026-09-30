# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1322 attackers** · **288,874 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 85 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 92 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 559 |
| `ssh-bruteforce` | 313 |
| `redis-exploit` | 258 |
| `mcp-abuse` | 82 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 20 |
| `docker-abuse` | 13 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 894 |
| `redis` | 266 |
| `mcp` | 118 |
| `llamacpp` | 74 |
| `vllm` | 45 |
| `jupyter` | 41 |
| `litellm` | 40 |
| `hfhub` | 35 |
| `docker` | 28 |
| `ollama` | 19 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 532 |
| `345gs5662d34` | 450 |
| `admin` | 267 |
| `ubuntu` | 113 |
| `administrator` | 82 |
| `admin1` | 64 |
| `user` | 56 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `test` | 51 |
| `admin123` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 452 |
| `345gs5662d34` | 450 |
| `123456` | 274 |
| `123` | 155 |
| `1234` | 138 |
| `12345678` | 82 |
| `admin` | 81 |
| `password` | 71 |
| `000000` | 68 |
| `12345` | 67 |
| `1` | 66 |
| `!QAZ2wsx` | 56 |
| `0` | 55 |
| `123456789` | 53 |
| `0000` | 53 |

### Top commands run

| command | times |
|---|---|
| `uname` | 582 |
| `echo` | 520 |
| `lscpu` | 508 |
| `crontab` | 506 |
| `cd` | 501 |
| `cat` | 500 |
| `top` | 465 |
| `ls` | 464 |
| `df` | 464 |
| `free` | 464 |
| `whoami` | 463 |
| `w` | 462 |
| `INFO` | 171 |
| `PING` | 105 |
| `canary_env` | 102 |


_Generated from first-party honeypot capture. CC BY 4.0._
