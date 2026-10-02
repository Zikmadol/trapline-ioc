# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1407 attackers** · **322,566 hostile actions** · covering 20 day(s) through 2026-10-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 97 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 98 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 598 |
| `ssh-bruteforce` | 335 |
| `redis-exploit` | 268 |
| `mcp-abuse` | 90 |
| `llamacpp-abuse` | 25 |
| `litellm-key-replay` | 21 |
| `docker-abuse` | 15 |
| `ollama-abuse` | 12 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 959 |
| `redis` | 276 |
| `mcp` | 127 |
| `llamacpp` | 80 |
| `vllm` | 48 |
| `jupyter` | 42 |
| `litellm` | 41 |
| `hfhub` | 37 |
| `docker` | 30 |
| `ollama` | 20 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 568 |
| `345gs5662d34` | 481 |
| `admin` | 293 |
| `ubuntu` | 130 |
| `administrator` | 88 |
| `admin1` | 66 |
| `user` | 62 |
| `test` | 61 |
| `admin2` | 57 |
| `adminuser` | 57 |
| `a` | 56 |
| `ai` | 56 |
| `AdminGPON` | 55 |
| `aaa` | 54 |
| `admin123` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 484 |
| `345gs5662d34` | 481 |
| `123456` | 307 |
| `123` | 184 |
| `1234` | 160 |
| `12345678` | 94 |
| `admin` | 90 |
| `password` | 76 |
| `000000` | 73 |
| `12345` | 72 |
| `1` | 71 |
| `!QAZ2wsx` | 63 |
| `0` | 60 |
| `123456789` | 58 |
| `0000` | 56 |

### Top commands run

| command | times |
|---|---|
| `uname` | 627 |
| `echo` | 559 |
| `lscpu` | 546 |
| `crontab` | 545 |
| `cd` | 537 |
| `cat` | 537 |
| `ls` | 496 |
| `top` | 496 |
| `df` | 495 |
| `free` | 495 |
| `whoami` | 494 |
| `w` | 493 |
| `INFO` | 179 |
| `canary_env` | 113 |
| `PING` | 112 |


_Generated from first-party honeypot capture. CC BY 4.0._
