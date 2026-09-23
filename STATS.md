# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**687 attackers** · **138,314 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 36 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 14 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 253 |
| `ssh-bruteforce` | 204 |
| `redis-exploit` | 131 |
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
| `ssh` | 467 |
| `redis` | 136 |
| `mcp` | 56 |
| `llamacpp` | 33 |
| `vllm` | 18 |
| `jupyter` | 15 |
| `docker` | 13 |
| `hfhub` | 12 |
| `ollama` | 6 |
| `litellm` | 5 |
| `ray` | 4 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 245 |
| `345gs5662d34` | 202 |
| `admin` | 148 |
| `administrator` | 38 |
| `ubuntu` | 35 |
| `admin1` | 34 |
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
| `345gs5662d34` | 202 |
| `3245gs5662d34` | 201 |
| `123456` | 125 |
| `123` | 67 |
| `1234` | 63 |
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
| `uname` | 262 |
| `echo` | 230 |
| `lscpu` | 225 |
| `crontab` | 222 |
| `cat` | 221 |
| `cd` | 220 |
| `ls` | 209 |
| `top` | 209 |
| `df` | 208 |
| `free` | 208 |
| `whoami` | 207 |
| `w` | 206 |
| `INFO` | 95 |
| `canary_env` | 57 |
| `CONFIG` | 42 |


_Generated from first-party honeypot capture. CC BY 4.0._
