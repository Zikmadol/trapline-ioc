# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1415 attackers** · **323,402 hostile actions** · covering 20 day(s) through 2026-10-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 98 |
| Used a planted canary credential | 2 |
| Seen on more than one sensor | 99 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 600 |
| `ssh-bruteforce` | 338 |
| `redis-exploit` | 268 |
| `mcp-abuse` | 91 |
| `llamacpp-abuse` | 25 |
| `litellm-key-replay` | 22 |
| `docker-abuse` | 15 |
| `ollama-abuse` | 12 |
| `vllm-abuse` | 5 |
| `canary-aws-key` | 4 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 965 |
| `redis` | 276 |
| `mcp` | 128 |
| `llamacpp` | 80 |
| `vllm` | 48 |
| `jupyter` | 42 |
| `litellm` | 42 |
| `hfhub` | 37 |
| `docker` | 30 |
| `ollama` | 20 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 571 |
| `345gs5662d34` | 482 |
| `admin` | 293 |
| `ubuntu` | 132 |
| `administrator` | 87 |
| `admin1` | 65 |
| `test` | 63 |
| `user` | 63 |
| `admin2` | 56 |
| `adminuser` | 56 |
| `AdminGPON` | 55 |
| `a` | 55 |
| `ai` | 55 |
| `aaa` | 53 |
| `ftpuser` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 485 |
| `345gs5662d34` | 482 |
| `123456` | 307 |
| `123` | 184 |
| `1234` | 161 |
| `12345678` | 94 |
| `admin` | 91 |
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
| `uname` | 629 |
| `echo` | 560 |
| `lscpu` | 547 |
| `crontab` | 546 |
| `cd` | 538 |
| `cat` | 538 |
| `ls` | 497 |
| `top` | 497 |
| `df` | 496 |
| `free` | 496 |
| `whoami` | 495 |
| `w` | 494 |
| `INFO` | 179 |
| `canary_env` | 114 |
| `PING` | 112 |


_Generated from first-party honeypot capture. CC BY 4.0._
