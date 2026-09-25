# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**844 attackers** · **179,017 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 47 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 326 |
| `ssh-bruteforce` | 225 |
| `redis-exploit` | 176 |
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
| `ssh` | 567 |
| `redis` | 181 |
| `mcp` | 76 |
| `llamacpp` | 52 |
| `vllm` | 28 |
| `jupyter` | 26 |
| `hfhub` | 19 |
| `docker` | 18 |
| `ollama` | 10 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 300 |
| `345gs5662d34` | 254 |
| `admin` | 173 |
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
| `345gs5662d34` | 254 |
| `3245gs5662d34` | 253 |
| `123456` | 148 |
| `123` | 91 |
| `1234` | 74 |
| `admin` | 60 |
| `000000` | 44 |
| `12345678` | 44 |
| `12345` | 39 |
| `!QAZ2wsx` | 38 |
| `123456789` | 37 |
| `0000` | 37 |
| `password` | 35 |
| `0` | 35 |
| `1` | 34 |

### Top commands run

| command | times |
|---|---|
| `uname` | 333 |
| `echo` | 296 |
| `lscpu` | 289 |
| `crontab` | 287 |
| `cat` | 284 |
| `cd` | 283 |
| `ls` | 265 |
| `top` | 265 |
| `df` | 264 |
| `free` | 264 |
| `whoami` | 263 |
| `w` | 262 |
| `INFO` | 121 |
| `canary_env` | 68 |
| `PING` | 62 |


_Generated from first-party honeypot capture. CC BY 4.0._
