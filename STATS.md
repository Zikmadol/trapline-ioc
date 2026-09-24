# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**749 attackers** · **156,747 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 41 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 17 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 278 |
| `ssh-bruteforce` | 212 |
| `redis-exploit` | 152 |
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
| `ssh` | 502 |
| `redis` | 157 |
| `mcp` | 69 |
| `llamacpp` | 39 |
| `vllm` | 24 |
| `jupyter` | 20 |
| `hfhub` | 15 |
| `docker` | 13 |
| `litellm` | 8 |
| `ollama` | 7 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 263 |
| `345gs5662d34` | 218 |
| `admin` | 157 |
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
| `345gs5662d34` | 218 |
| `3245gs5662d34` | 217 |
| `123456` | 134 |
| `123` | 77 |
| `1234` | 68 |
| `admin` | 53 |
| `12345678` | 42 |
| `000000` | 41 |
| `12345` | 35 |
| `!QAZ2wsx` | 34 |
| `0000` | 32 |
| `password` | 31 |
| `123456789` | 31 |
| `0` | 31 |
| `!Q2w3e4r` | 29 |

### Top commands run

| command | times |
|---|---|
| `uname` | 286 |
| `echo` | 252 |
| `lscpu` | 247 |
| `crontab` | 245 |
| `cat` | 242 |
| `cd` | 241 |
| `ls` | 228 |
| `top` | 228 |
| `df` | 227 |
| `free` | 227 |
| `whoami` | 226 |
| `w` | 225 |
| `INFO` | 107 |
| `canary_env` | 63 |
| `PING` | 52 |


_Generated from first-party honeypot capture. CC BY 4.0._
