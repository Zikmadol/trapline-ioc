# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1149 attackers** · **247,662 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 67 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 69 |
| Stage-2 hosts named in payloads | 20 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 470 |
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
| `ssh` | 763 |
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
| `root` | 432 |
| `345gs5662d34` | 374 |
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
| `3245gs5662d34` | 374 |
| `345gs5662d34` | 374 |
| `123456` | 207 |
| `123` | 123 |
| `1234` | 100 |
| `admin` | 73 |
| `12345678` | 63 |
| `000000` | 56 |
| `12345` | 54 |
| `password` | 50 |
| `1` | 49 |
| `!QAZ2wsx` | 49 |
| `0` | 47 |
| `0000` | 46 |
| `!Q2w3e4r` | 45 |

### Top commands run

| command | times |
|---|---|
| `uname` | 480 |
| `echo` | 428 |
| `lscpu` | 420 |
| `crontab` | 417 |
| `cd` | 416 |
| `cat` | 416 |
| `top` | 387 |
| `ls` | 386 |
| `df` | 386 |
| `free` | 386 |
| `whoami` | 385 |
| `w` | 384 |
| `INFO` | 156 |
| `canary_env` | 95 |
| `PING` | 92 |


_Generated from first-party honeypot capture. CC BY 4.0._
