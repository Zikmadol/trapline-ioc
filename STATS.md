# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**920 attackers** · **183,954 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 49 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 34 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 358 |
| `ssh-bruteforce` | 232 |
| `redis-exploit` | 196 |
| `mcp-abuse` | 64 |
| `llamacpp-abuse` | 19 |
| `ollama-abuse` | 10 |
| `docker-abuse` | 9 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 606 |
| `redis` | 202 |
| `mcp` | 87 |
| `llamacpp` | 58 |
| `vllm` | 31 |
| `jupyter` | 27 |
| `hfhub` | 21 |
| `docker` | 18 |
| `ollama` | 12 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 331 |
| `345gs5662d34` | 284 |
| `admin` | 183 |
| `administrator` | 55 |
| `ubuntu` | 49 |
| `admin1` | 43 |
| `aaa` | 37 |
| `admin2` | 36 |
| `AdminGPON` | 35 |
| `a` | 35 |
| `adminuser` | 35 |
| `ai` | 35 |
| `Asalem` | 33 |
| `adm1n` | 32 |
| `admin123` | 32 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 284 |
| `3245gs5662d34` | 283 |
| `123456` | 161 |
| `123` | 101 |
| `1234` | 81 |
| `admin` | 63 |
| `12345678` | 47 |
| `000000` | 45 |
| `12345` | 41 |
| `123456789` | 40 |
| `!QAZ2wsx` | 39 |
| `password` | 38 |
| `1` | 38 |
| `0000` | 37 |
| `0` | 35 |

### Top commands run

| command | times |
|---|---|
| `uname` | 366 |
| `echo` | 327 |
| `lscpu` | 319 |
| `cat` | 317 |
| `crontab` | 316 |
| `cd` | 316 |
| `top` | 294 |
| `ls` | 293 |
| `df` | 293 |
| `free` | 293 |
| `whoami` | 292 |
| `w` | 291 |
| `INFO` | 134 |
| `canary_env` | 80 |
| `PING` | 71 |


_Generated from first-party honeypot capture. CC BY 4.0._
