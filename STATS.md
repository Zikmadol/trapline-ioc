# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**867 attackers** · **179,760 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 47 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 337 |
| `ssh-bruteforce` | 227 |
| `redis-exploit` | 182 |
| `mcp-abuse` | 59 |
| `llamacpp-abuse` | 17 |
| `docker-abuse` | 9 |
| `ollama-abuse` | 8 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 580 |
| `redis` | 188 |
| `mcp` | 80 |
| `llamacpp` | 54 |
| `vllm` | 28 |
| `jupyter` | 26 |
| `hfhub` | 20 |
| `docker` | 18 |
| `ollama` | 10 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 311 |
| `345gs5662d34` | 264 |
| `admin` | 175 |
| `administrator` | 50 |
| `ubuntu` | 43 |
| `admin1` | 42 |
| `aaa` | 36 |
| `admin2` | 35 |
| `AdminGPON` | 34 |
| `a` | 34 |
| `adminuser` | 34 |
| `ai` | 34 |
| `Asalem` | 32 |
| `admin123` | 32 |
| `Caps` | 31 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 264 |
| `3245gs5662d34` | 263 |
| `123456` | 152 |
| `123` | 91 |
| `1234` | 77 |
| `admin` | 60 |
| `000000` | 44 |
| `12345678` | 44 |
| `12345` | 40 |
| `123456789` | 38 |
| `!QAZ2wsx` | 38 |
| `0000` | 37 |
| `password` | 36 |
| `1` | 35 |
| `0` | 35 |

### Top commands run

| command | times |
|---|---|
| `uname` | 343 |
| `echo` | 306 |
| `lscpu` | 299 |
| `crontab` | 296 |
| `cat` | 295 |
| `cd` | 294 |
| `top` | 275 |
| `ls` | 274 |
| `df` | 274 |
| `free` | 273 |
| `whoami` | 273 |
| `w` | 272 |
| `INFO` | 124 |
| `canary_env` | 72 |
| `PING` | 66 |


_Generated from first-party honeypot capture. CC BY 4.0._
