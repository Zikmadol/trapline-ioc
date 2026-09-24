# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**732 attackers** · **148,963 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 39 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 17 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 268 |
| `ssh-bruteforce` | 210 |
| `redis-exploit` | 148 |
| `mcp-abuse` | 50 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 8 |
| `ollama-abuse` | 5 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 490 |
| `redis` | 153 |
| `mcp` | 66 |
| `llamacpp` | 37 |
| `vllm` | 22 |
| `jupyter` | 20 |
| `hfhub` | 13 |
| `docker` | 13 |
| `litellm` | 8 |
| `ollama` | 7 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 254 |
| `345gs5662d34` | 212 |
| `admin` | 155 |
| `administrator` | 40 |
| `ubuntu` | 38 |
| `admin1` | 37 |
| `admin2` | 31 |
| `adminuser` | 30 |
| `AdminGPON` | 29 |
| `a` | 29 |
| `admin123` | 29 |
| `ai` | 29 |
| `aaa` | 28 |
| `Asalem` | 27 |
| `Caps` | 27 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 212 |
| `3245gs5662d34` | 210 |
| `123456` | 131 |
| `123` | 73 |
| `1234` | 65 |
| `admin` | 53 |
| `12345678` | 41 |
| `000000` | 40 |
| `12345` | 35 |
| `0000` | 32 |
| `!QAZ2wsx` | 32 |
| `0` | 31 |
| `password` | 30 |
| `123456789` | 29 |
| `051178` | 29 |

### Top commands run

| command | times |
|---|---|
| `uname` | 277 |
| `echo` | 243 |
| `lscpu` | 238 |
| `crontab` | 235 |
| `cat` | 234 |
| `cd` | 233 |
| `ls` | 220 |
| `top` | 220 |
| `df` | 219 |
| `free` | 219 |
| `whoami` | 218 |
| `w` | 217 |
| `INFO` | 105 |
| `canary_env` | 62 |
| `PING` | 51 |


_Generated from first-party honeypot capture. CC BY 4.0._
