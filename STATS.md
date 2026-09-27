# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1002 attackers** · **218,560 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 57 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 54 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 391 |
| `ssh-bruteforce` | 248 |
| `redis-exploit` | 213 |
| `mcp-abuse` | 70 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `litellm-key-replay` | 4 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 658 |
| `redis` | 220 |
| `mcp` | 96 |
| `llamacpp` | 63 |
| `vllm` | 37 |
| `jupyter` | 34 |
| `hfhub` | 31 |
| `docker` | 22 |
| `litellm` | 17 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 366 |
| `345gs5662d34` | 309 |
| `admin` | 199 |
| `administrator` | 62 |
| `ubuntu` | 54 |
| `admin1` | 47 |
| `aaa` | 42 |
| `AdminGPON` | 40 |
| `a` | 40 |
| `admin2` | 40 |
| `adminuser` | 40 |
| `ai` | 40 |
| `Asalem` | 38 |
| `admin123` | 38 |
| `Caps` | 37 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 309 |
| `3245gs5662d34` | 308 |
| `123456` | 178 |
| `123` | 111 |
| `1234` | 91 |
| `admin` | 63 |
| `12345678` | 51 |
| `000000` | 50 |
| `12345` | 45 |
| `!QAZ2wsx` | 43 |
| `0000` | 42 |
| `0` | 42 |
| `123456789` | 41 |
| `!Q2w3e4r` | 41 |
| `1` | 40 |

### Top commands run

| command | times |
|---|---|
| `uname` | 399 |
| `echo` | 357 |
| `lscpu` | 349 |
| `crontab` | 346 |
| `cd` | 344 |
| `cat` | 344 |
| `top` | 320 |
| `ls` | 319 |
| `df` | 319 |
| `free` | 319 |
| `whoami` | 318 |
| `w` | 317 |
| `INFO` | 145 |
| `canary_env` | 87 |
| `PING` | 81 |


_Generated from first-party honeypot capture. CC BY 4.0._
