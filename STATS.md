# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**837 attackers** · **178,876 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 47 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 324 |
| `ssh-bruteforce` | 222 |
| `redis-exploit` | 174 |
| `mcp-abuse` | 56 |
| `llamacpp-abuse` | 16 |
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
| `ssh` | 562 |
| `redis` | 179 |
| `mcp` | 76 |
| `llamacpp` | 51 |
| `vllm` | 28 |
| `jupyter` | 25 |
| `hfhub` | 18 |
| `docker` | 18 |
| `ollama` | 10 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 299 |
| `345gs5662d34` | 253 |
| `admin` | 171 |
| `administrator` | 50 |
| `ubuntu` | 43 |
| `admin1` | 42 |
| `aaa` | 35 |
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
| `345gs5662d34` | 253 |
| `3245gs5662d34` | 252 |
| `123456` | 147 |
| `123` | 90 |
| `1234` | 73 |
| `admin` | 58 |
| `000000` | 44 |
| `12345678` | 43 |
| `!QAZ2wsx` | 38 |
| `12345` | 37 |
| `123456789` | 37 |
| `0000` | 37 |
| `password` | 35 |
| `0` | 35 |
| `1` | 34 |

### Top commands run

| command | times |
|---|---|
| `uname` | 332 |
| `echo` | 294 |
| `lscpu` | 288 |
| `crontab` | 286 |
| `cat` | 282 |
| `cd` | 281 |
| `ls` | 264 |
| `top` | 264 |
| `df` | 263 |
| `free` | 263 |
| `whoami` | 262 |
| `w` | 261 |
| `INFO` | 120 |
| `canary_env` | 68 |
| `PING` | 61 |


_Generated from first-party honeypot capture. CC BY 4.0._
