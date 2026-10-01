# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1353 attackers** · **298,644 hostile actions** · covering 19 day(s) through 2026-10-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 88 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 93 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 572 |
| `ssh-bruteforce` | 324 |
| `redis-exploit` | 260 |
| `mcp-abuse` | 85 |
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
| `ssh` | 919 |
| `redis` | 268 |
| `mcp` | 122 |
| `llamacpp` | 76 |
| `vllm` | 48 |
| `jupyter` | 42 |
| `litellm` | 41 |
| `hfhub` | 36 |
| `docker` | 29 |
| `ollama` | 19 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 544 |
| `345gs5662d34` | 460 |
| `admin` | 277 |
| `ubuntu` | 118 |
| `administrator` | 88 |
| `admin1` | 66 |
| `user` | 61 |
| `admin2` | 57 |
| `a` | 56 |
| `ai` | 55 |
| `test` | 54 |
| `aaa` | 54 |
| `adminuser` | 54 |
| `AdminGPON` | 53 |
| `admin123` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 463 |
| `345gs5662d34` | 460 |
| `123456` | 283 |
| `123` | 163 |
| `1234` | 149 |
| `admin` | 85 |
| `12345678` | 85 |
| `password` | 72 |
| `000000` | 70 |
| `12345` | 69 |
| `1` | 68 |
| `!QAZ2wsx` | 59 |
| `123456789` | 56 |
| `0` | 56 |
| `0000` | 55 |

### Top commands run

| command | times |
|---|---|
| `uname` | 595 |
| `echo` | 532 |
| `lscpu` | 520 |
| `crontab` | 519 |
| `cd` | 511 |
| `cat` | 510 |
| `top` | 475 |
| `ls` | 474 |
| `df` | 474 |
| `free` | 474 |
| `whoami` | 473 |
| `w` | 472 |
| `INFO` | 173 |
| `canary_env` | 106 |
| `PING` | 105 |


_Generated from first-party honeypot capture. CC BY 4.0._
