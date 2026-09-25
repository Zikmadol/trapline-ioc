# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**800 attackers** · **169,656 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 45 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 300 |
| `ssh-bruteforce` | 218 |
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
| `ssh` | 534 |
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
| `root` | 279 |
| `345gs5662d34` | 235 |
| `admin` | 163 |
| `administrator` | 49 |
| `admin1` | 41 |
| `ubuntu` | 40 |
| `admin2` | 33 |
| `adminuser` | 33 |
| `ai` | 33 |
| `AdminGPON` | 32 |
| `a` | 32 |
| `aaa` | 32 |
| `Asalem` | 30 |
| `admin123` | 30 |
| `admin1234` | 30 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 235 |
| `3245gs5662d34` | 234 |
| `123456` | 140 |
| `123` | 82 |
| `1234` | 70 |
| `admin` | 54 |
| `000000` | 43 |
| `12345678` | 43 |
| `12345` | 37 |
| `123456789` | 37 |
| `!QAZ2wsx` | 37 |
| `0000` | 36 |
| `password` | 34 |
| `0` | 34 |
| `1` | 32 |

### Top commands run

| command | times |
|---|---|
| `uname` | 308 |
| `echo` | 275 |
| `lscpu` | 269 |
| `crontab` | 267 |
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
