# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1235 attackers** · **277,722 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 77 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 79 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 512 |
| `ssh-bruteforce` | 297 |
| `redis-exploit` | 246 |
| `mcp-abuse` | 78 |
| `llamacpp-abuse` | 22 |
| `litellm-key-replay` | 17 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 829 |
| `redis` | 254 |
| `mcp` | 112 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 38 |
| `hfhub` | 35 |
| `litellm` | 33 |
| `docker` | 26 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 482 |
| `345gs5662d34` | 409 |
| `admin` | 249 |
| `ubuntu` | 95 |
| `administrator` | 77 |
| `admin1` | 63 |
| `a` | 53 |
| `admin2` | 53 |
| `ai` | 53 |
| `AdminGPON` | 51 |
| `aaa` | 51 |
| `adminuser` | 50 |
| `admin123` | 48 |
| `Asalem` | 47 |
| `Caps` | 47 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 410 |
| `345gs5662d34` | 409 |
| `123456` | 233 |
| `123` | 134 |
| `1234` | 116 |
| `admin` | 77 |
| `12345678` | 73 |
| `000000` | 65 |
| `password` | 62 |
| `12345` | 60 |
| `1` | 58 |
| `!QAZ2wsx` | 54 |
| `0` | 52 |
| `0000` | 51 |
| `!Q2w3e4r` | 50 |

### Top commands run

| command | times |
|---|---|
| `uname` | 529 |
| `echo` | 471 |
| `lscpu` | 461 |
| `crontab` | 458 |
| `cd` | 457 |
| `cat` | 456 |
| `top` | 423 |
| `ls` | 422 |
| `df` | 422 |
| `free` | 422 |
| `whoami` | 421 |
| `w` | 420 |
| `INFO` | 165 |
| `PING` | 99 |
| `canary_env` | 97 |


_Generated from first-party honeypot capture. CC BY 4.0._
