# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**969 attackers** · **198,437 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 54 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 49 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 378 |
| `ssh-bruteforce` | 242 |
| `redis-exploit` | 206 |
| `mcp-abuse` | 69 |
| `llamacpp-abuse` | 21 |
| `ollama-abuse` | 10 |
| `docker-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 636 |
| `redis` | 213 |
| `mcp` | 93 |
| `llamacpp` | 61 |
| `vllm` | 35 |
| `jupyter` | 31 |
| `hfhub` | 27 |
| `docker` | 20 |
| `ollama` | 14 |
| `litellm` | 11 |
| `ray` | 7 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 351 |
| `345gs5662d34` | 300 |
| `admin` | 190 |
| `administrator` | 58 |
| `ubuntu` | 53 |
| `admin1` | 45 |
| `aaa` | 39 |
| `admin2` | 38 |
| `AdminGPON` | 37 |
| `a` | 37 |
| `adminuser` | 37 |
| `ai` | 37 |
| `Asalem` | 35 |
| `admin123` | 35 |
| `Caps` | 34 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 300 |
| `3245gs5662d34` | 299 |
| `123456` | 172 |
| `123` | 106 |
| `1234` | 88 |
| `admin` | 62 |
| `12345678` | 50 |
| `000000` | 47 |
| `12345` | 44 |
| `123456789` | 41 |
| `!QAZ2wsx` | 41 |
| `0000` | 40 |
| `password` | 39 |
| `0` | 39 |
| `1` | 38 |

### Top commands run

| command | times |
|---|---|
| `uname` | 387 |
| `echo` | 345 |
| `lscpu` | 337 |
| `crontab` | 334 |
| `cd` | 334 |
| `cat` | 334 |
| `top` | 310 |
| `ls` | 309 |
| `df` | 309 |
| `free` | 309 |
| `whoami` | 308 |
| `w` | 307 |
| `INFO` | 143 |
| `canary_env` | 86 |
| `PING` | 78 |


_Generated from first-party honeypot capture. CC BY 4.0._
