# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1363 attackers** · **307,177 hostile actions** · covering 19 day(s) through 2026-10-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 92 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 95 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 578 |
| `ssh-bruteforce` | 324 |
| `redis-exploit` | 262 |
| `mcp-abuse` | 87 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 21 |
| `docker-abuse` | 14 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 925 |
| `redis` | 270 |
| `mcp` | 124 |
| `llamacpp` | 76 |
| `vllm` | 48 |
| `jupyter` | 42 |
| `litellm` | 41 |
| `hfhub` | 36 |
| `docker` | 29 |
| `ollama` | 19 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 546 |
| `345gs5662d34` | 461 |
| `admin` | 280 |
| `ubuntu` | 121 |
| `administrator` | 89 |
| `admin1` | 67 |
| `user` | 61 |
| `admin2` | 58 |
| `a` | 57 |
| `ai` | 57 |
| `AdminGPON` | 55 |
| `aaa` | 55 |
| `adminuser` | 55 |
| `test` | 54 |
| `admin123` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 464 |
| `345gs5662d34` | 461 |
| `123456` | 284 |
| `123` | 167 |
| `1234` | 150 |
| `admin` | 86 |
| `12345678` | 86 |
| `password` | 73 |
| `000000` | 71 |
| `12345` | 70 |
| `1` | 68 |
| `!QAZ2wsx` | 61 |
| `0` | 59 |
| `123456789` | 57 |
| `0000` | 56 |

### Top commands run

| command | times |
|---|---|
| `uname` | 601 |
| `echo` | 535 |
| `lscpu` | 523 |
| `crontab` | 522 |
| `cd` | 514 |
| `cat` | 513 |
| `top` | 476 |
| `ls` | 475 |
| `df` | 475 |
| `free` | 475 |
| `whoami` | 474 |
| `w` | 473 |
| `INFO` | 174 |
| `canary_env` | 108 |
| `PING` | 106 |


_Generated from first-party honeypot capture. CC BY 4.0._
