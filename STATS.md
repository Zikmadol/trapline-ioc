# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**724 attackers** · **145,396 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 38 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 17 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 266 |
| `ssh-bruteforce` | 210 |
| `redis-exploit` | 145 |
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
| `ssh` | 488 |
| `redis` | 150 |
| `mcp` | 63 |
| `llamacpp` | 36 |
| `vllm` | 21 |
| `jupyter` | 17 |
| `docker` | 13 |
| `hfhub` | 12 |
| `litellm` | 8 |
| `ollama` | 6 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 253 |
| `345gs5662d34` | 211 |
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
| `345gs5662d34` | 211 |
| `3245gs5662d34` | 209 |
| `123456` | 131 |
| `123` | 72 |
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
| `uname` | 275 |
| `echo` | 241 |
| `lscpu` | 236 |
| `crontab` | 233 |
| `cat` | 233 |
| `cd` | 232 |
| `ls` | 219 |
| `top` | 219 |
| `df` | 218 |
| `free` | 218 |
| `whoami` | 217 |
| `w` | 216 |
| `INFO` | 104 |
| `canary_env` | 61 |
| `PING` | 48 |


_Generated from first-party honeypot capture. CC BY 4.0._
