# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**866 attackers** · **179,687 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 47 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 336 |
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
| `ssh` | 579 |
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
| `root` | 310 |
| `345gs5662d34` | 263 |
| `admin` | 174 |
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
| `345gs5662d34` | 263 |
| `3245gs5662d34` | 262 |
| `123456` | 152 |
| `123` | 91 |
| `1234` | 76 |
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
| `uname` | 342 |
| `echo` | 305 |
| `lscpu` | 298 |
| `crontab` | 295 |
| `cat` | 294 |
| `cd` | 293 |
| `top` | 274 |
| `ls` | 273 |
| `df` | 273 |
| `free` | 272 |
| `whoami` | 272 |
| `w` | 271 |
| `INFO` | 124 |
| `canary_env` | 72 |
| `PING` | 66 |


_Generated from first-party honeypot capture. CC BY 4.0._
