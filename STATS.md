# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1317 attackers** · **288,314 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 84 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 92 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 558 |
| `ssh-bruteforce` | 310 |
| `redis-exploit` | 258 |
| `mcp-abuse` | 81 |
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
| `ssh` | 890 |
| `redis` | 266 |
| `mcp` | 117 |
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
| `root` | 529 |
| `345gs5662d34` | 449 |
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
| `3245gs5662d34` | 451 |
| `345gs5662d34` | 449 |
| `123456` | 273 |
| `123` | 154 |
| `1234` | 138 |
| `12345678` | 82 |
| `admin` | 81 |
| `password` | 71 |
| `000000` | 68 |
| `12345` | 67 |
| `1` | 66 |
| `!QAZ2wsx` | 55 |
| `0` | 54 |
| `123456789` | 53 |
| `0000` | 53 |

### Top commands run

| command | times |
|---|---|
| `uname` | 580 |
| `echo` | 518 |
| `lscpu` | 506 |
| `crontab` | 504 |
| `cd` | 500 |
| `cat` | 499 |
| `top` | 464 |
| `ls` | 463 |
| `df` | 463 |
| `free` | 463 |
| `whoami` | 462 |
| `w` | 461 |
| `INFO` | 171 |
| `PING` | 105 |
| `canary_env` | 101 |


_Generated from first-party honeypot capture. CC BY 4.0._
