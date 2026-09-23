# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**671 attackers** · **137,510 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 36 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 12 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 243 |
| `ssh-bruteforce` | 203 |
| `redis-exploit` | 129 |
| `mcp-abuse` | 44 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 7 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 454 |
| `redis` | 134 |
| `mcp` | 55 |
| `llamacpp` | 33 |
| `vllm` | 18 |
| `jupyter` | 15 |
| `hfhub` | 11 |
| `docker` | 11 |
| `ollama` | 6 |
| `litellm` | 4 |
| `ray` | 4 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 238 |
| `345gs5662d34` | 194 |
| `admin` | 147 |
| `administrator` | 37 |
| `admin1` | 33 |
| `ubuntu` | 33 |
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
| `345gs5662d34` | 194 |
| `3245gs5662d34` | 193 |
| `123456` | 124 |
| `123` | 65 |
| `1234` | 59 |
| `admin` | 50 |
| `000000` | 39 |
| `12345678` | 38 |
| `12345` | 33 |
| `0000` | 30 |
| `!QAZ2wsx` | 30 |
| `123456789` | 29 |
| `0` | 29 |
| `password` | 28 |
| `00000000` | 27 |

### Top commands run

| command | times |
|---|---|
| `uname` | 254 |
| `echo` | 221 |
| `lscpu` | 217 |
| `crontab` | 215 |
| `cat` | 212 |
| `cd` | 211 |
| `ls` | 201 |
| `top` | 201 |
| `df` | 200 |
| `whoami` | 200 |
| `free` | 199 |
| `w` | 199 |
| `INFO` | 93 |
| `canary_env` | 56 |
| `CONFIG` | 42 |


_Generated from first-party honeypot capture. CC BY 4.0._
