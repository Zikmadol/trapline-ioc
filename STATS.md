# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1307 attackers** · **288,031 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 84 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 90 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 557 |
| `ssh-bruteforce` | 308 |
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
| `ssh` | 887 |
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
| `root` | 525 |
| `345gs5662d34` | 448 |
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
| `3245gs5662d34` | 450 |
| `345gs5662d34` | 448 |
| `123456` | 270 |
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
| `uname` | 578 |
| `echo` | 516 |
| `lscpu` | 505 |
| `crontab` | 502 |
| `cd` | 499 |
| `cat` | 498 |
| `top` | 463 |
| `ls` | 462 |
| `df` | 462 |
| `free` | 462 |
| `whoami` | 461 |
| `w` | 460 |
| `INFO` | 168 |
| `PING` | 103 |
| `canary_env` | 100 |


_Generated from first-party honeypot capture. CC BY 4.0._
