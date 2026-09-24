# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**721 attackers** · **145,189 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 38 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 17 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 265 |
| `ssh-bruteforce` | 209 |
| `redis-exploit` | 144 |
| `mcp-abuse` | 49 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 8 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 486 |
| `redis` | 149 |
| `mcp` | 63 |
| `llamacpp` | 36 |
| `vllm` | 20 |
| `jupyter` | 17 |
| `docker` | 13 |
| `hfhub` | 12 |
| `litellm` | 8 |
| `ollama` | 6 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 252 |
| `345gs5662d34` | 210 |
| `admin` | 153 |
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
| `345gs5662d34` | 210 |
| `3245gs5662d34` | 208 |
| `123456` | 130 |
| `123` | 71 |
| `1234` | 64 |
| `admin` | 52 |
| `000000` | 40 |
| `12345678` | 40 |
| `12345` | 34 |
| `0000` | 31 |
| `!QAZ2wsx` | 31 |
| `password` | 30 |
| `0` | 30 |
| `123456789` | 29 |
| `00000000` | 28 |

### Top commands run

| command | times |
|---|---|
| `uname` | 274 |
| `echo` | 240 |
| `lscpu` | 235 |
| `crontab` | 232 |
| `cat` | 232 |
| `cd` | 231 |
| `ls` | 218 |
| `top` | 218 |
| `df` | 217 |
| `free` | 217 |
| `whoami` | 216 |
| `w` | 215 |
| `INFO` | 103 |
| `canary_env` | 61 |
| `PING` | 47 |


_Generated from first-party honeypot capture. CC BY 4.0._
