# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1163 attackers** · **248,528 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 69 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 72 |
| Stage-2 hosts named in payloads | 21 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 478 |
| `ssh-bruteforce` | 275 |
| `redis-exploit` | 233 |
| `mcp-abuse` | 76 |
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
| `ssh` | 773 |
| `redis` | 241 |
| `mcp` | 108 |
| `llamacpp` | 70 |
| `vllm` | 42 |
| `jupyter` | 38 |
| `hfhub` | 34 |
| `litellm` | 33 |
| `docker` | 24 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 441 |
| `345gs5662d34` | 380 |
| `admin` | 227 |
| `ubuntu` | 73 |
| `administrator` | 71 |
| `admin1` | 55 |
| `admin2` | 47 |
| `ai` | 47 |
| `AdminGPON` | 46 |
| `a` | 46 |
| `aaa` | 46 |
| `adminuser` | 45 |
| `admin123` | 43 |
| `Asalem` | 42 |
| `Caps` | 42 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 380 |
| `345gs5662d34` | 380 |
| `123456` | 211 |
| `123` | 126 |
| `1234` | 104 |
| `admin` | 74 |
| `12345678` | 65 |
| `000000` | 56 |
| `password` | 55 |
| `12345` | 55 |
| `1` | 52 |
| `!QAZ2wsx` | 49 |
| `0` | 47 |
| `123456789` | 46 |
| `0000` | 46 |

### Top commands run

| command | times |
|---|---|
| `uname` | 488 |
| `echo` | 434 |
| `lscpu` | 426 |
| `crontab` | 423 |
| `cd` | 422 |
| `cat` | 422 |
| `top` | 393 |
| `ls` | 392 |
| `df` | 392 |
| `free` | 392 |
| `whoami` | 391 |
| `w` | 390 |
| `INFO` | 157 |
| `canary_env` | 95 |
| `PING` | 92 |


_Generated from first-party honeypot capture. CC BY 4.0._
