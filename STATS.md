# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1233 attackers** · **277,532 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 77 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 78 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 511 |
| `ssh-bruteforce` | 297 |
| `redis-exploit` | 245 |
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
| `ssh` | 828 |
| `redis` | 253 |
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
| `root` | 481 |
| `345gs5662d34` | 408 |
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
| `3245gs5662d34` | 408 |
| `345gs5662d34` | 408 |
| `123456` | 232 |
| `123` | 134 |
| `1234` | 116 |
| `admin` | 77 |
| `12345678` | 73 |
| `000000` | 65 |
| `password` | 62 |
| `12345` | 60 |
| `1` | 57 |
| `!QAZ2wsx` | 54 |
| `0` | 52 |
| `0000` | 51 |
| `!Q2w3e4r` | 50 |

### Top commands run

| command | times |
|---|---|
| `uname` | 528 |
| `echo` | 470 |
| `lscpu` | 460 |
| `crontab` | 457 |
| `cd` | 455 |
| `cat` | 455 |
| `top` | 422 |
| `ls` | 421 |
| `df` | 421 |
| `free` | 421 |
| `whoami` | 420 |
| `w` | 419 |
| `INFO` | 164 |
| `PING` | 98 |
| `canary_env` | 97 |


_Generated from first-party honeypot capture. CC BY 4.0._
