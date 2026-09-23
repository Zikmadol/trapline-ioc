# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**617 attackers** · **134,375 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 35 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 11 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 219 |
| `ssh-bruteforce` | 192 |
| `redis-exploit` | 117 |
| `mcp-abuse` | 41 |
| `llamacpp-abuse` | 14 |
| `docker-abuse` | 7 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 418 |
| `redis` | 121 |
| `mcp` | 50 |
| `llamacpp` | 31 |
| `vllm` | 16 |
| `jupyter` | 11 |
| `docker` | 11 |
| `hfhub` | 9 |
| `ray` | 4 |
| `ollama` | 4 |
| `litellm` | 3 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 218 |
| `345gs5662d34` | 173 |
| `admin` | 134 |
| `administrator` | 35 |
| `admin1` | 31 |
| `admin2` | 29 |
| `ubuntu` | 29 |
| `AdminGPON` | 27 |
| `a` | 27 |
| `aaa` | 27 |
| `admin123` | 27 |
| `adminuser` | 27 |
| `ai` | 27 |
| `Asalem` | 25 |
| `Caps` | 25 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 173 |
| `3245gs5662d34` | 171 |
| `123456` | 114 |
| `123` | 57 |
| `1234` | 55 |
| `admin` | 44 |
| `000000` | 38 |
| `12345678` | 37 |
| `12345` | 32 |
| `0000` | 30 |
| `!QAZ2wsx` | 30 |
| `123456789` | 29 |
| `0` | 29 |
| `password` | 28 |
| `00000000` | 27 |

### Top commands run

| command | times |
|---|---|
| `uname` | 230 |
| `echo` | 199 |
| `lscpu` | 195 |
| `crontab` | 193 |
| `cat` | 188 |
| `cd` | 186 |
| `ls` | 179 |
| `top` | 179 |
| `df` | 178 |
| `whoami` | 178 |
| `free` | 177 |
| `w` | 177 |
| `INFO` | 84 |
| `canary_env` | 51 |
| `CONFIG` | 41 |


_Generated from first-party honeypot capture. CC BY 4.0._
