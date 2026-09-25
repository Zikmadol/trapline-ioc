# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**797 attackers** · **167,744 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 44 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 299 |
| `ssh-bruteforce` | 216 |
| `redis-exploit` | 170 |
| `mcp-abuse` | 53 |
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
| `ssh` | 531 |
| `redis` | 175 |
| `mcp` | 72 |
| `llamacpp` | 47 |
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
| `root` | 278 |
| `345gs5662d34` | 235 |
| `admin` | 162 |
| `administrator` | 48 |
| `admin1` | 40 |
| `ubuntu` | 40 |
| `admin2` | 33 |
| `AdminGPON` | 32 |
| `a` | 32 |
| `aaa` | 32 |
| `adminuser` | 32 |
| `ai` | 32 |
| `Asalem` | 30 |
| `admin123` | 30 |
| `aishani` | 30 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 235 |
| `3245gs5662d34` | 234 |
| `123456` | 140 |
| `123` | 81 |
| `1234` | 70 |
| `admin` | 54 |
| `000000` | 43 |
| `12345678` | 43 |
| `12345` | 37 |
| `123456789` | 37 |
| `!QAZ2wsx` | 36 |
| `0000` | 35 |
| `password` | 34 |
| `0` | 33 |
| `!Q2w3e4r` | 32 |

### Top commands run

| command | times |
|---|---|
| `uname` | 307 |
| `echo` | 274 |
| `lscpu` | 268 |
| `crontab` | 266 |
| `cat` | 260 |
| `cd` | 259 |
| `ls` | 246 |
| `top` | 246 |
| `df` | 245 |
| `free` | 245 |
| `whoami` | 244 |
| `w` | 243 |
| `INFO` | 116 |
| `canary_env` | 65 |
| `PING` | 59 |


_Generated from first-party honeypot capture. CC BY 4.0._
