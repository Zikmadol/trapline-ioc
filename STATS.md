# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**828 attackers** · **176,991 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 47 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 320 |
| `ssh-bruteforce` | 221 |
| `redis-exploit` | 171 |
| `mcp-abuse` | 55 |
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
| `ssh` | 557 |
| `redis` | 176 |
| `mcp` | 75 |
| `llamacpp` | 49 |
| `vllm` | 27 |
| `jupyter` | 23 |
| `hfhub` | 18 |
| `docker` | 18 |
| `ollama` | 10 |
| `litellm` | 9 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 298 |
| `345gs5662d34` | 252 |
| `admin` | 168 |
| `administrator` | 50 |
| `admin1` | 42 |
| `ubuntu` | 42 |
| `admin2` | 35 |
| `AdminGPON` | 34 |
| `a` | 34 |
| `aaa` | 34 |
| `adminuser` | 34 |
| `ai` | 34 |
| `Asalem` | 32 |
| `admin123` | 32 |
| `Caps` | 31 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 252 |
| `3245gs5662d34` | 251 |
| `123456` | 147 |
| `123` | 88 |
| `1234` | 73 |
| `admin` | 57 |
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
| `uname` | 328 |
| `echo` | 293 |
| `lscpu` | 287 |
| `crontab` | 285 |
| `cat` | 278 |
| `cd` | 277 |
| `ls` | 263 |
| `top` | 263 |
| `df` | 262 |
| `free` | 262 |
| `whoami` | 261 |
| `w` | 260 |
| `INFO` | 117 |
| `canary_env` | 67 |
| `PING` | 60 |


_Generated from first-party honeypot capture. CC BY 4.0._
