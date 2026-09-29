# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1212 attackers** · **267,005 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 74 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 76 |
| Stage-2 hosts named in payloads | 21 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 504 |
| `ssh-bruteforce` | 290 |
| `redis-exploit` | 240 |
| `mcp-abuse` | 77 |
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
| `ssh` | 814 |
| `redis` | 248 |
| `mcp` | 109 |
| `llamacpp` | 71 |
| `vllm` | 42 |
| `jupyter` | 38 |
| `hfhub` | 34 |
| `litellm` | 33 |
| `docker` | 25 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 471 |
| `345gs5662d34` | 401 |
| `admin` | 243 |
| `ubuntu` | 91 |
| `administrator` | 75 |
| `admin1` | 61 |
| `a` | 51 |
| `ai` | 51 |
| `admin2` | 50 |
| `AdminGPON` | 49 |
| `aaa` | 49 |
| `adminuser` | 48 |
| `admin123` | 46 |
| `Asalem` | 45 |
| `Caps` | 45 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 401 |
| `345gs5662d34` | 401 |
| `123456` | 226 |
| `123` | 133 |
| `1234` | 114 |
| `admin` | 76 |
| `12345678` | 71 |
| `password` | 62 |
| `000000` | 62 |
| `12345` | 60 |
| `1` | 57 |
| `!QAZ2wsx` | 52 |
| `0` | 50 |
| `0000` | 49 |
| `!Q2w3e4r` | 48 |

### Top commands run

| command | times |
|---|---|
| `uname` | 518 |
| `echo` | 460 |
| `lscpu` | 451 |
| `crontab` | 448 |
| `cat` | 448 |
| `cd` | 447 |
| `top` | 415 |
| `ls` | 414 |
| `df` | 414 |
| `free` | 414 |
| `whoami` | 413 |
| `w` | 412 |
| `INFO` | 162 |
| `canary_env` | 96 |
| `PING` | 95 |


_Generated from first-party honeypot capture. CC BY 4.0._
