# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1006 attackers** · **218,873 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 57 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 56 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 391 |
| `ssh-bruteforce` | 249 |
| `redis-exploit` | 214 |
| `mcp-abuse` | 70 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `litellm-key-replay` | 6 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 659 |
| `redis` | 221 |
| `mcp` | 97 |
| `llamacpp` | 63 |
| `vllm` | 37 |
| `jupyter` | 35 |
| `hfhub` | 31 |
| `docker` | 22 |
| `litellm` | 19 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 366 |
| `345gs5662d34` | 310 |
| `admin` | 200 |
| `administrator` | 62 |
| `ubuntu` | 54 |
| `admin1` | 48 |
| `aaa` | 42 |
| `AdminGPON` | 41 |
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
| `345gs5662d34` | 310 |
| `3245gs5662d34` | 309 |
| `123456` | 179 |
| `123` | 111 |
| `1234` | 91 |
| `admin` | 63 |
| `12345678` | 52 |
| `000000` | 50 |
| `12345` | 45 |
| `!QAZ2wsx` | 44 |
| `0000` | 42 |
| `0` | 42 |
| `123456789` | 41 |
| `!Q2w3e4r` | 41 |
| `1` | 40 |

### Top commands run

| command | times |
|---|---|
| `uname` | 400 |
| `echo` | 358 |
| `lscpu` | 350 |
| `crontab` | 347 |
| `cd` | 345 |
| `cat` | 345 |
| `top` | 321 |
| `ls` | 320 |
| `df` | 320 |
| `free` | 320 |
| `whoami` | 319 |
| `w` | 318 |
| `INFO` | 145 |
| `canary_env` | 87 |
| `PING` | 81 |


_Generated from first-party honeypot capture. CC BY 4.0._
