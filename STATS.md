# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**601 attackers** · **133,761 hostile actions** · covering 10 day(s) through 2026-09-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 35 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 9 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 211 |
| `ssh-bruteforce` | 192 |
| `redis-exploit` | 113 |
| `mcp-abuse` | 39 |
| `llamacpp-abuse` | 13 |
| `docker-abuse` | 6 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 409 |
| `redis` | 116 |
| `mcp` | 46 |
| `llamacpp` | 28 |
| `vllm` | 16 |
| `jupyter` | 11 |
| `docker` | 10 |
| `hfhub` | 8 |
| `ray` | 4 |
| `ollama` | 4 |
| `litellm` | 3 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 211 |
| `345gs5662d34` | 165 |
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
| `345gs5662d34` | 165 |
| `3245gs5662d34` | 163 |
| `123456` | 110 |
| `123` | 56 |
| `1234` | 55 |
| `admin` | 44 |
| `000000` | 38 |
| `12345678` | 37 |
| `12345` | 32 |
| `0000` | 30 |
| `!QAZ2wsx` | 30 |
| `123456789` | 29 |
| `0` | 29 |
| `password` | 27 |
| `00000000` | 27 |

### Top commands run

| command | times |
|---|---|
| `uname` | 222 |
| `echo` | 191 |
| `lscpu` | 187 |
| `crontab` | 185 |
| `cat` | 180 |
| `cd` | 178 |
| `ls` | 171 |
| `top` | 171 |
| `df` | 170 |
| `whoami` | 170 |
| `free` | 169 |
| `w` | 169 |
| `INFO` | 82 |
| `canary_env` | 49 |
| `CONFIG` | 41 |


_Generated from first-party honeypot capture. CC BY 4.0._
