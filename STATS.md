# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**683 attackers** · **138,047 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 36 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 13 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 250 |
| `ssh-bruteforce` | 204 |
| `redis-exploit` | 130 |
| `mcp-abuse` | 45 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 9 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 463 |
| `redis` | 135 |
| `mcp` | 56 |
| `llamacpp` | 33 |
| `vllm` | 18 |
| `jupyter` | 15 |
| `docker` | 13 |
| `hfhub` | 11 |
| `ollama` | 6 |
| `litellm` | 5 |
| `ray` | 4 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 243 |
| `345gs5662d34` | 200 |
| `admin` | 148 |
| `administrator` | 37 |
| `admin1` | 34 |
| `ubuntu` | 34 |
| `admin2` | 29 |
| `AdminGPON` | 27 |
| `a` | 27 |
| `aaa` | 27 |
| `admin123` | 27 |
| `adminuser` | 27 |
| `ai` | 27 |
| `agent` | 26 |
| `airflow` | 26 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 200 |
| `3245gs5662d34` | 199 |
| `123456` | 125 |
| `123` | 67 |
| `1234` | 61 |
| `admin` | 50 |
| `000000` | 39 |
| `12345678` | 38 |
| `12345` | 33 |
| `password` | 30 |
| `0000` | 30 |
| `!QAZ2wsx` | 30 |
| `123456789` | 29 |
| `0` | 29 |
| `00000000` | 27 |

### Top commands run

| command | times |
|---|---|
| `uname` | 260 |
| `echo` | 228 |
| `lscpu` | 223 |
| `crontab` | 220 |
| `cat` | 219 |
| `cd` | 217 |
| `ls` | 206 |
| `df` | 206 |
| `free` | 206 |
| `top` | 206 |
| `whoami` | 205 |
| `w` | 204 |
| `INFO` | 94 |
| `canary_env` | 57 |
| `CONFIG` | 42 |


_Generated from first-party honeypot capture. CC BY 4.0._
