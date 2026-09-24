# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**728 attackers** · **145,698 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 38 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 17 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 267 |
| `ssh-bruteforce` | 210 |
| `redis-exploit` | 146 |
| `mcp-abuse` | 50 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 8 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 489 |
| `redis` | 151 |
| `mcp` | 66 |
| `llamacpp` | 37 |
| `vllm` | 21 |
| `jupyter` | 18 |
| `docker` | 13 |
| `hfhub` | 12 |
| `litellm` | 8 |
| `ollama` | 6 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 254 |
| `345gs5662d34` | 212 |
| `admin` | 154 |
| `administrator` | 40 |
| `ubuntu` | 38 |
| `admin1` | 36 |
| `admin2` | 30 |
| `adminuser` | 29 |
| `AdminGPON` | 28 |
| `a` | 28 |
| `aaa` | 28 |
| `admin123` | 28 |
| `ai` | 28 |
| `agent` | 27 |
| `airflow` | 27 |

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
| `0000` | 31 |
| `!QAZ2wsx` | 31 |
| `password` | 30 |
| `0` | 30 |
| `123456789` | 29 |
| `00000000` | 28 |

### Top commands run

| command | times |
|---|---|
| `uname` | 276 |
| `echo` | 242 |
| `lscpu` | 237 |
| `crontab` | 234 |
| `cat` | 234 |
| `cd` | 233 |
| `ls` | 220 |
| `top` | 220 |
| `df` | 219 |
| `free` | 219 |
| `whoami` | 218 |
| `w` | 217 |
| `INFO` | 104 |
| `canary_env` | 62 |
| `PING` | 49 |


_Generated from first-party honeypot capture. CC BY 4.0._
