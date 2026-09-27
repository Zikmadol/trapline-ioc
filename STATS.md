# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**990 attackers** · **210,030 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 56 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 50 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 389 |
| `ssh-bruteforce` | 244 |
| `redis-exploit` | 208 |
| `mcp-abuse` | 70 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 11 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `litellm-key-replay` | 4 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 650 |
| `redis` | 215 |
| `mcp` | 95 |
| `llamacpp` | 62 |
| `vllm` | 36 |
| `jupyter` | 33 |
| `hfhub` | 30 |
| `docker` | 21 |
| `litellm` | 16 |
| `ollama` | 15 |
| `ray` | 7 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 360 |
| `345gs5662d34` | 308 |
| `admin` | 195 |
| `administrator` | 60 |
| `ubuntu` | 53 |
| `admin1` | 46 |
| `aaa` | 41 |
| `AdminGPON` | 39 |
| `a` | 39 |
| `admin2` | 39 |
| `adminuser` | 39 |
| `ai` | 39 |
| `Asalem` | 37 |
| `admin123` | 37 |
| `Caps` | 36 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 308 |
| `3245gs5662d34` | 307 |
| `123456` | 175 |
| `123` | 111 |
| `1234` | 89 |
| `admin` | 63 |
| `000000` | 49 |
| `12345678` | 49 |
| `12345` | 43 |
| `!QAZ2wsx` | 42 |
| `0000` | 41 |
| `0` | 41 |
| `password` | 40 |
| `1` | 40 |
| `123456789` | 40 |

### Top commands run

| command | times |
|---|---|
| `uname` | 397 |
| `echo` | 355 |
| `lscpu` | 347 |
| `crontab` | 344 |
| `cd` | 343 |
| `cat` | 343 |
| `top` | 319 |
| `ls` | 318 |
| `df` | 318 |
| `free` | 318 |
| `whoami` | 317 |
| `w` | 316 |
| `INFO` | 143 |
| `canary_env` | 87 |
| `PING` | 78 |


_Generated from first-party honeypot capture. CC BY 4.0._
