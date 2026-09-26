# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**977 attackers** · **198,686 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 54 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 50 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 382 |
| `ssh-bruteforce` | 243 |
| `redis-exploit` | 208 |
| `mcp-abuse` | 70 |
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
| `ssh` | 641 |
| `redis` | 215 |
| `mcp` | 95 |
| `llamacpp` | 62 |
| `vllm` | 36 |
| `jupyter` | 33 |
| `hfhub` | 30 |
| `docker` | 20 |
| `ollama` | 15 |
| `litellm` | 12 |
| `ray` | 7 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 355 |
| `345gs5662d34` | 303 |
| `admin` | 193 |
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
| `345gs5662d34` | 303 |
| `3245gs5662d34` | 302 |
| `123456` | 173 |
| `123` | 108 |
| `1234` | 88 |
| `admin` | 62 |
| `12345678` | 50 |
| `000000` | 47 |
| `12345` | 44 |
| `123456789` | 41 |
| `!QAZ2wsx` | 41 |
| `password` | 40 |
| `0000` | 40 |
| `0` | 39 |
| `1` | 38 |

### Top commands run

| command | times |
|---|---|
| `uname` | 391 |
| `echo` | 349 |
| `lscpu` | 341 |
| `crontab` | 338 |
| `cd` | 338 |
| `cat` | 338 |
| `top` | 314 |
| `ls` | 313 |
| `df` | 313 |
| `free` | 313 |
| `whoami` | 312 |
| `w` | 311 |
| `INFO` | 143 |
| `canary_env` | 87 |
| `PING` | 78 |


_Generated from first-party honeypot capture. CC BY 4.0._
