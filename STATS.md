# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**782 attackers** · **163,558 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 44 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 291 |
| `ssh-bruteforce` | 214 |
| `redis-exploit` | 166 |
| `mcp-abuse` | 53 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 8 |
| `ollama-abuse` | 7 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 521 |
| `redis` | 171 |
| `mcp` | 72 |
| `llamacpp` | 47 |
| `vllm` | 26 |
| `jupyter` | 22 |
| `hfhub` | 18 |
| `docker` | 15 |
| `litellm` | 9 |
| `ollama` | 9 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 270 |
| `345gs5662d34` | 228 |
| `admin` | 161 |
| `administrator` | 47 |
| `admin1` | 40 |
| `ubuntu` | 40 |
| `admin2` | 32 |
| `ai` | 32 |
| `AdminGPON` | 31 |
| `a` | 31 |
| `aaa` | 31 |
| `adminuser` | 31 |
| `Asalem` | 30 |
| `actian` | 29 |
| `admin123` | 29 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 228 |
| `3245gs5662d34` | 227 |
| `123456` | 138 |
| `123` | 81 |
| `1234` | 71 |
| `admin` | 54 |
| `12345678` | 44 |
| `000000` | 42 |
| `12345` | 37 |
| `123456789` | 36 |
| `!QAZ2wsx` | 36 |
| `0000` | 35 |
| `0` | 33 |
| `1` | 32 |
| `password` | 31 |

### Top commands run

| command | times |
|---|---|
| `uname` | 299 |
| `echo` | 266 |
| `lscpu` | 260 |
| `crontab` | 258 |
| `cat` | 252 |
| `cd` | 251 |
| `ls` | 238 |
| `top` | 238 |
| `df` | 237 |
| `free` | 237 |
| `whoami` | 236 |
| `w` | 235 |
| `INFO` | 114 |
| `canary_env` | 65 |
| `PING` | 59 |


_Generated from first-party honeypot capture. CC BY 4.0._
