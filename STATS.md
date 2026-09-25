# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**806 attackers** · **172,997 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 46 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 305 |
| `ssh-bruteforce` | 218 |
| `redis-exploit` | 170 |
| `mcp-abuse` | 54 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 9 |
| `ollama-abuse` | 7 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 539 |
| `redis` | 175 |
| `mcp` | 73 |
| `llamacpp` | 48 |
| `vllm` | 26 |
| `jupyter` | 22 |
| `hfhub` | 18 |
| `docker` | 16 |
| `litellm` | 9 |
| `ollama` | 9 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 285 |
| `345gs5662d34` | 239 |
| `admin` | 167 |
| `administrator` | 49 |
| `admin1` | 41 |
| `ubuntu` | 40 |
| `admin2` | 34 |
| `AdminGPON` | 33 |
| `a` | 33 |
| `aaa` | 33 |
| `adminuser` | 33 |
| `ai` | 33 |
| `Asalem` | 31 |
| `admin123` | 31 |
| `aishani` | 31 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 239 |
| `3245gs5662d34` | 238 |
| `123456` | 142 |
| `123` | 82 |
| `1234` | 71 |
| `admin` | 55 |
| `000000` | 44 |
| `12345678` | 43 |
| `12345` | 37 |
| `123456789` | 37 |
| `!QAZ2wsx` | 37 |
| `0000` | 36 |
| `password` | 34 |
| `0` | 34 |
| `!Q2w3e4r` | 33 |

### Top commands run

| command | times |
|---|---|
| `uname` | 313 |
| `echo` | 279 |
| `lscpu` | 273 |
| `crontab` | 271 |
| `cat` | 264 |
| `cd` | 263 |
| `ls` | 250 |
| `top` | 250 |
| `df` | 249 |
| `free` | 249 |
| `whoami` | 248 |
| `w` | 247 |
| `INFO` | 116 |
| `canary_env` | 66 |
| `PING` | 59 |


_Generated from first-party honeypot capture. CC BY 4.0._
