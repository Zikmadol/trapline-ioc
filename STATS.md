# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1176 attackers** · **252,855 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 72 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 74 |
| Stage-2 hosts named in payloads | 21 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 484 |
| `ssh-bruteforce` | 280 |
| `redis-exploit` | 235 |
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
| `ssh` | 784 |
| `redis` | 243 |
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
| `root` | 449 |
| `345gs5662d34` | 381 |
| `admin` | 230 |
| `ubuntu` | 75 |
| `administrator` | 73 |
| `admin1` | 57 |
| `ai` | 49 |
| `admin2` | 48 |
| `a` | 47 |
| `AdminGPON` | 46 |
| `aaa` | 46 |
| `adminuser` | 46 |
| `Asalem` | 43 |
| `abigail` | 43 |
| `adm1n` | 43 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 381 |
| `345gs5662d34` | 381 |
| `123456` | 212 |
| `123` | 129 |
| `1234` | 105 |
| `admin` | 75 |
| `12345678` | 65 |
| `password` | 57 |
| `000000` | 56 |
| `12345` | 55 |
| `1` | 54 |
| `!QAZ2wsx` | 50 |
| `0` | 49 |
| `0000` | 48 |
| `!Q2w3e4r` | 47 |

### Top commands run

| command | times |
|---|---|
| `uname` | 493 |
| `echo` | 439 |
| `lscpu` | 430 |
| `crontab` | 427 |
| `cat` | 425 |
| `cd` | 424 |
| `top` | 395 |
| `ls` | 394 |
| `df` | 394 |
| `free` | 394 |
| `whoami` | 393 |
| `w` | 392 |
| `INFO` | 158 |
| `canary_env` | 95 |
| `PING` | 93 |


_Generated from first-party honeypot capture. CC BY 4.0._
