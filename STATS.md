# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**712 attackers** · **144,707 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 38 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 15 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 263 |
| `ssh-bruteforce` | 208 |
| `redis-exploit` | 137 |
| `mcp-abuse` | 49 |
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
| `ssh` | 482 |
| `redis` | 142 |
| `mcp` | 62 |
| `llamacpp` | 35 |
| `vllm` | 18 |
| `jupyter` | 16 |
| `docker` | 13 |
| `hfhub` | 12 |
| `litellm` | 7 |
| `ollama` | 6 |
| `ray` | 4 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 252 |
| `345gs5662d34` | 210 |
| `admin` | 151 |
| `administrator` | 40 |
| `ubuntu` | 37 |
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
| `123456` | 129 |
| `123` | 69 |
| `1234` | 64 |
| `admin` | 51 |
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
| `uname` | 272 |
| `echo` | 240 |
| `lscpu` | 235 |
| `crontab` | 232 |
| `cat` | 230 |
| `cd` | 229 |
| `ls` | 218 |
| `top` | 218 |
| `df` | 217 |
| `free` | 217 |
| `whoami` | 216 |
| `w` | 215 |
| `INFO` | 99 |
| `canary_env` | 61 |
| `CONFIG` | 44 |


_Generated from first-party honeypot capture. CC BY 4.0._
