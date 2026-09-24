# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**740 attackers** · **153,645 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 40 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 17 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 271 |
| `ssh-bruteforce` | 213 |
| `redis-exploit` | 149 |
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
| `redis` | 154 |
| `mcp` | 68 |
| `llamacpp` | 38 |
| `vllm` | 24 |
| `jupyter` | 20 |
| `hfhub` | 13 |
| `docker` | 13 |
| `litellm` | 8 |
| `ollama` | 7 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 260 |
| `345gs5662d34` | 213 |
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
| `345gs5662d34` | 213 |
| `3245gs5662d34` | 211 |
| `123456` | 131 |
| `123` | 74 |
| `1234` | 66 |
| `admin` | 53 |
| `000000` | 41 |
| `12345678` | 41 |
| `12345` | 35 |
| `!QAZ2wsx` | 33 |
| `0000` | 32 |
| `password` | 31 |
| `0` | 31 |
| `123456789` | 29 |
| `00000000` | 29 |

### Top commands run

| command | times |
|---|---|
| `uname` | 279 |
| `echo` | 246 |
| `lscpu` | 241 |
| `crontab` | 238 |
| `cat` | 236 |
| `cd` | 235 |
| `ls` | 222 |
| `top` | 222 |
| `df` | 221 |
| `free` | 221 |
| `whoami` | 220 |
| `w` | 219 |
| `INFO` | 106 |
| `canary_env` | 63 |
| `PING` | 52 |


_Generated from first-party honeypot capture. CC BY 4.0._
