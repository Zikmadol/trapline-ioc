# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1324 attackers** · **289,204 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 85 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 92 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 560 |
| `ssh-bruteforce` | 312 |
| `redis-exploit` | 259 |
| `mcp-abuse` | 82 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 21 |
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
| `redis` | 267 |
| `mcp` | 118 |
| `llamacpp` | 75 |
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
| `345gs5662d34` | 451 |
| `admin` | 267 |
| `ubuntu` | 114 |
| `administrator` | 82 |
| `admin1` | 64 |
| `user` | 56 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `test` | 52 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `admin123` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 453 |
| `345gs5662d34` | 451 |
| `123456` | 275 |
| `123` | 156 |
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
| `uname` | 583 |
| `echo` | 521 |
| `lscpu` | 509 |
| `crontab` | 507 |
| `cd` | 502 |
| `cat` | 501 |
| `top` | 466 |
| `ls` | 465 |
| `df` | 465 |
| `free` | 465 |
| `whoami` | 464 |
| `w` | 463 |
| `INFO` | 172 |
| `PING` | 105 |
| `canary_env` | 103 |


_Generated from first-party honeypot capture. CC BY 4.0._
