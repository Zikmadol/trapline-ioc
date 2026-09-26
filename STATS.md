# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**954 attackers** · **197,872 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 54 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 44 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 371 |
| `ssh-bruteforce` | 241 |
| `redis-exploit` | 206 |
| `mcp-abuse` | 65 |
| `llamacpp-abuse` | 20 |
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
| `ssh` | 628 |
| `redis` | 212 |
| `mcp` | 89 |
| `llamacpp` | 60 |
| `vllm` | 34 |
| `jupyter` | 31 |
| `hfhub` | 26 |
| `docker` | 19 |
| `ollama` | 12 |
| `litellm` | 11 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 345 |
| `345gs5662d34` | 295 |
| `admin` | 189 |
| `administrator` | 58 |
| `ubuntu` | 52 |
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
| `345gs5662d34` | 295 |
| `3245gs5662d34` | 294 |
| `123456` | 170 |
| `123` | 103 |
| `1234` | 87 |
| `admin` | 62 |
| `12345678` | 49 |
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
| `uname` | 382 |
| `echo` | 340 |
| `lscpu` | 332 |
| `crontab` | 329 |
| `cat` | 329 |
| `cd` | 328 |
| `top` | 305 |
| `ls` | 304 |
| `df` | 304 |
| `free` | 304 |
| `whoami` | 303 |
| `w` | 302 |
| `INFO` | 142 |
| `canary_env` | 81 |
| `PING` | 76 |


_Generated from first-party honeypot capture. CC BY 4.0._
