# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**826 attackers** · **174,660 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 47 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 318 |
| `ssh-bruteforce` | 221 |
| `redis-exploit` | 171 |
| `mcp-abuse` | 55 |
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
| `ssh` | 555 |
| `redis` | 176 |
| `mcp` | 75 |
| `llamacpp` | 49 |
| `vllm` | 27 |
| `jupyter` | 23 |
| `hfhub` | 18 |
| `docker` | 18 |
| `ollama` | 10 |
| `litellm` | 9 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 296 |
| `345gs5662d34` | 251 |
| `admin` | 168 |
| `administrator` | 49 |
| `admin1` | 41 |
| `ubuntu` | 41 |
| `admin2` | 35 |
| `a` | 34 |
| `AdminGPON` | 33 |
| `aaa` | 33 |
| `adminuser` | 33 |
| `ai` | 33 |
| `Asalem` | 32 |
| `admin123` | 31 |
| `aishani` | 31 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 251 |
| `3245gs5662d34` | 250 |
| `123456` | 148 |
| `123` | 88 |
| `1234` | 73 |
| `admin` | 57 |
| `000000` | 44 |
| `12345678` | 44 |
| `12345` | 38 |
| `123456789` | 38 |
| `!QAZ2wsx` | 38 |
| `0000` | 36 |
| `password` | 35 |
| `1` | 34 |
| `0` | 34 |

### Top commands run

| command | times |
|---|---|
| `uname` | 326 |
| `echo` | 292 |
| `lscpu` | 286 |
| `crontab` | 284 |
| `cat` | 276 |
| `cd` | 275 |
| `ls` | 262 |
| `top` | 262 |
| `df` | 261 |
| `free` | 261 |
| `whoami` | 260 |
| `w` | 259 |
| `INFO` | 117 |
| `canary_env` | 67 |
| `PING` | 60 |


_Generated from first-party honeypot capture. CC BY 4.0._
