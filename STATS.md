# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1303 attackers** · **287,914 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 84 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 90 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 556 |
| `ssh-bruteforce` | 305 |
| `redis-exploit` | 254 |
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
| `ssh` | 883 |
| `redis` | 262 |
| `mcp` | 116 |
| `llamacpp` | 73 |
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
| `root` | 523 |
| `345gs5662d34` | 447 |
| `admin` | 267 |
| `ubuntu` | 112 |
| `administrator` | 82 |
| `admin1` | 64 |
| `user` | 56 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `test` | 50 |
| `admin123` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 449 |
| `345gs5662d34` | 447 |
| `123456` | 269 |
| `123` | 152 |
| `1234` | 136 |
| `12345678` | 82 |
| `admin` | 81 |
| `password` | 71 |
| `000000` | 68 |
| `1` | 66 |
| `12345` | 66 |
| `!QAZ2wsx` | 55 |
| `0` | 54 |
| `123456789` | 53 |
| `0000` | 53 |

### Top commands run

| command | times |
|---|---|
| `uname` | 577 |
| `echo` | 514 |
| `lscpu` | 504 |
| `crontab` | 501 |
| `cd` | 498 |
| `cat` | 497 |
| `top` | 462 |
| `ls` | 461 |
| `df` | 461 |
| `free` | 461 |
| `whoami` | 460 |
| `w` | 459 |
| `INFO` | 168 |
| `PING` | 103 |
| `canary_env` | 100 |


_Generated from first-party honeypot capture. CC BY 4.0._
