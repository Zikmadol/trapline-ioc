# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**984 attackers** · **201,952 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 54 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 50 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 387 |
| `ssh-bruteforce` | 244 |
| `redis-exploit` | 208 |
| `mcp-abuse` | 70 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 11 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 648 |
| `redis` | 215 |
| `mcp` | 95 |
| `llamacpp` | 62 |
| `vllm` | 36 |
| `jupyter` | 33 |
| `hfhub` | 30 |
| `docker` | 21 |
| `ollama` | 15 |
| `litellm` | 12 |
| `ray` | 7 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 359 |
| `345gs5662d34` | 308 |
| `admin` | 193 |
| `administrator` | 59 |
| `ubuntu` | 53 |
| `admin1` | 45 |
| `aaa` | 39 |
| `AdminGPON` | 38 |
| `a` | 38 |
| `admin2` | 38 |
| `adminuser` | 38 |
| `ai` | 38 |
| `admin123` | 36 |
| `Asalem` | 35 |
| `Caps` | 35 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 308 |
| `3245gs5662d34` | 307 |
| `123456` | 175 |
| `123` | 110 |
| `1234` | 88 |
| `admin` | 62 |
| `12345678` | 49 |
| `000000` | 48 |
| `12345` | 43 |
| `!QAZ2wsx` | 41 |
| `password` | 40 |
| `123456789` | 40 |
| `0000` | 40 |
| `0` | 40 |
| `1` | 39 |

### Top commands run

| command | times |
|---|---|
| `uname` | 396 |
| `echo` | 354 |
| `lscpu` | 346 |
| `crontab` | 343 |
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
