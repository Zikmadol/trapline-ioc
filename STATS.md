# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1372 attackers** · **308,797 hostile actions** · covering 19 day(s) through 2026-10-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 92 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 95 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 583 |
| `ssh-bruteforce` | 327 |
| `redis-exploit` | 263 |
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
| `ssh` | 933 |
| `redis` | 271 |
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
| `root` | 553 |
| `345gs5662d34` | 466 |
| `admin` | 286 |
| `ubuntu` | 129 |
| `administrator` | 89 |
| `admin1` | 67 |
| `user` | 61 |
| `admin2` | 58 |
| `adminuser` | 58 |
| `test` | 57 |
| `a` | 57 |
| `ai` | 57 |
| `AdminGPON` | 55 |
| `aaa` | 55 |
| `admin123` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 469 |
| `345gs5662d34` | 466 |
| `123456` | 293 |
| `123` | 174 |
| `1234` | 156 |
| `12345678` | 89 |
| `admin` | 87 |
| `password` | 73 |
| `1` | 71 |
| `000000` | 71 |
| `12345` | 71 |
| `!QAZ2wsx` | 61 |
| `0` | 59 |
| `123456789` | 57 |
| `0000` | 56 |

### Top commands run

| command | times |
|---|---|
| `uname` | 607 |
| `echo` | 540 |
| `lscpu` | 528 |
| `crontab` | 527 |
| `cd` | 520 |
| `cat` | 519 |
| `top` | 481 |
| `ls` | 480 |
| `df` | 480 |
| `free` | 480 |
| `whoami` | 479 |
| `w` | 478 |
| `INFO` | 174 |
| `canary_env` | 108 |
| `PING` | 106 |


_Generated from first-party honeypot capture. CC BY 4.0._
