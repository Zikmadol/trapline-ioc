# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**742 attackers** · **155,682 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 40 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 17 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 273 |
| `ssh-bruteforce` | 211 |
| `redis-exploit` | 151 |
| `mcp-abuse` | 51 |
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
| `ssh` | 496 |
| `redis` | 156 |
| `mcp` | 68 |
| `llamacpp` | 38 |
| `vllm` | 24 |
| `jupyter` | 20 |
| `hfhub` | 14 |
| `docker` | 13 |
| `litellm` | 8 |
| `ollama` | 7 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 260 |
| `345gs5662d34` | 214 |
| `admin` | 156 |
| `administrator` | 41 |
| `ubuntu` | 39 |
| `admin1` | 37 |
| `admin2` | 31 |
| `adminuser` | 30 |
| `AdminGPON` | 29 |
| `a` | 29 |
| `aaa` | 29 |
| `admin123` | 29 |
| `ai` | 29 |
| `agent` | 28 |
| `airflow` | 28 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 214 |
| `3245gs5662d34` | 213 |
| `123456` | 131 |
| `123` | 75 |
| `1234` | 67 |
| `admin` | 53 |
| `000000` | 41 |
| `12345678` | 41 |
| `12345` | 35 |
| `!QAZ2wsx` | 33 |
| `0000` | 32 |
| `password` | 31 |
| `0` | 31 |
| `123456789` | 30 |
| `00000000` | 29 |

### Top commands run

| command | times |
|---|---|
| `uname` | 281 |
| `echo` | 248 |
| `lscpu` | 243 |
| `crontab` | 240 |
| `cat` | 238 |
| `cd` | 237 |
| `ls` | 224 |
| `top` | 224 |
| `df` | 223 |
| `free` | 223 |
| `whoami` | 222 |
| `w` | 221 |
| `INFO` | 106 |
| `canary_env` | 63 |
| `PING` | 52 |


_Generated from first-party honeypot capture. CC BY 4.0._
