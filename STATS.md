# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**778 attackers** · **161,425 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 43 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 288 |
| `ssh-bruteforce` | 213 |
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
| `ssh` | 517 |
| `redis` | 171 |
| `mcp` | 72 |
| `llamacpp` | 46 |
| `vllm` | 26 |
| `jupyter` | 21 |
| `hfhub` | 18 |
| `docker` | 15 |
| `litellm` | 9 |
| `ollama` | 9 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 268 |
| `345gs5662d34` | 226 |
| `admin` | 160 |
| `administrator` | 45 |
| `admin1` | 39 |
| `ubuntu` | 39 |
| `AdminGPON` | 31 |
| `a` | 31 |
| `admin2` | 31 |
| `adminuser` | 31 |
| `ai` | 31 |
| `aaa` | 30 |
| `Asalem` | 29 |
| `admin123` | 29 |
| `aishani` | 29 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 226 |
| `3245gs5662d34` | 225 |
| `123456` | 137 |
| `123` | 81 |
| `1234` | 70 |
| `admin` | 54 |
| `12345678` | 43 |
| `000000` | 41 |
| `12345` | 35 |
| `!QAZ2wsx` | 35 |
| `123456789` | 34 |
| `0000` | 33 |
| `password` | 31 |
| `1` | 31 |
| `0` | 31 |

### Top commands run

| command | times |
|---|---|
| `uname` | 296 |
| `echo` | 263 |
| `lscpu` | 257 |
| `crontab` | 255 |
| `cat` | 250 |
| `cd` | 249 |
| `ls` | 236 |
| `top` | 236 |
| `df` | 235 |
| `free` | 235 |
| `whoami` | 234 |
| `w` | 233 |
| `INFO` | 114 |
| `canary_env` | 65 |
| `PING` | 59 |


_Generated from first-party honeypot capture. CC BY 4.0._
