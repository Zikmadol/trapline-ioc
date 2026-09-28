# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1142 attackers** · **247,302 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 67 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 69 |
| Stage-2 hosts named in payloads | 20 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 463 |
| `ssh-bruteforce` | 274 |
| `redis-exploit` | 230 |
| `mcp-abuse` | 76 |
| `llamacpp-abuse` | 22 |
| `litellm-key-replay` | 16 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 756 |
| `redis` | 238 |
| `mcp` | 107 |
| `llamacpp` | 67 |
| `vllm` | 42 |
| `jupyter` | 37 |
| `hfhub` | 34 |
| `litellm` | 32 |
| `docker` | 22 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 428 |
| `345gs5662d34` | 367 |
| `admin` | 226 |
| `administrator` | 71 |
| `ubuntu` | 70 |
| `admin1` | 54 |
| `admin2` | 47 |
| `ai` | 47 |
| `AdminGPON` | 46 |
| `aaa` | 46 |
| `a` | 45 |
| `adminuser` | 45 |
| `admin123` | 43 |
| `Asalem` | 42 |
| `Caps` | 42 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 367 |
| `345gs5662d34` | 367 |
| `123456` | 202 |
| `123` | 123 |
| `1234` | 100 |
| `admin` | 73 |
| `12345678` | 62 |
| `000000` | 56 |
| `12345` | 53 |
| `password` | 50 |
| `1` | 49 |
| `!QAZ2wsx` | 49 |
| `0` | 47 |
| `0000` | 46 |
| `!Q2w3e4r` | 45 |

### Top commands run

| command | times |
|---|---|
| `uname` | 473 |
| `echo` | 421 |
| `lscpu` | 413 |
| `crontab` | 410 |
| `cd` | 409 |
| `cat` | 409 |
| `top` | 380 |
| `ls` | 379 |
| `df` | 379 |
| `free` | 379 |
| `whoami` | 378 |
| `w` | 377 |
| `INFO` | 156 |
| `canary_env` | 95 |
| `PING` | 92 |


_Generated from first-party honeypot capture. CC BY 4.0._
