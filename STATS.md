# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1340 attackers** · **295,681 hostile actions** · covering 19 day(s) through 2026-10-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 87 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 93 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 565 |
| `ssh-bruteforce` | 319 |
| `redis-exploit` | 260 |
| `mcp-abuse` | 85 |
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
| `ssh` | 907 |
| `redis` | 268 |
| `mcp` | 122 |
| `llamacpp` | 76 |
| `vllm` | 48 |
| `jupyter` | 42 |
| `litellm` | 41 |
| `hfhub` | 36 |
| `docker` | 28 |
| `ollama` | 19 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 536 |
| `345gs5662d34` | 454 |
| `admin` | 273 |
| `ubuntu` | 114 |
| `administrator` | 83 |
| `admin1` | 65 |
| `user` | 56 |
| `admin2` | 56 |
| `a` | 55 |
| `ai` | 55 |
| `test` | 54 |
| `AdminGPON` | 53 |
| `aaa` | 53 |
| `adminuser` | 53 |
| `admin123` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 456 |
| `345gs5662d34` | 454 |
| `123456` | 277 |
| `123` | 160 |
| `1234` | 141 |
| `admin` | 83 |
| `12345678` | 83 |
| `password` | 72 |
| `000000` | 69 |
| `12345` | 68 |
| `1` | 67 |
| `!QAZ2wsx` | 58 |
| `123456789` | 56 |
| `0` | 56 |
| `0000` | 54 |

### Top commands run

| command | times |
|---|---|
| `uname` | 588 |
| `echo` | 525 |
| `lscpu` | 513 |
| `crontab` | 512 |
| `cd` | 505 |
| `cat` | 504 |
| `top` | 469 |
| `ls` | 468 |
| `df` | 468 |
| `free` | 468 |
| `whoami` | 467 |
| `w` | 466 |
| `INFO` | 173 |
| `canary_env` | 106 |
| `PING` | 105 |


_Generated from first-party honeypot capture. CC BY 4.0._
