# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**699 attackers** · **143,613 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 37 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 14 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 258 |
| `ssh-bruteforce` | 204 |
| `redis-exploit` | 135 |
| `mcp-abuse` | 47 |
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
| `ssh` | 472 |
| `redis` | 140 |
| `mcp` | 59 |
| `llamacpp` | 34 |
| `vllm` | 18 |
| `jupyter` | 16 |
| `docker` | 13 |
| `hfhub` | 12 |
| `ollama` | 6 |
| `litellm` | 5 |
| `ray` | 4 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 247 |
| `345gs5662d34` | 205 |
| `admin` | 149 |
| `administrator` | 39 |
| `admin1` | 35 |
| `ubuntu` | 35 |
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
| `345gs5662d34` | 205 |
| `3245gs5662d34` | 203 |
| `123456` | 126 |
| `123` | 68 |
| `1234` | 63 |
| `admin` | 50 |
| `000000` | 40 |
| `12345678` | 40 |
| `12345` | 33 |
| `0000` | 31 |
| `!QAZ2wsx` | 31 |
| `password` | 30 |
| `0` | 30 |
| `123456789` | 29 |
| `00000000` | 28 |

### Top commands run

| command | times |
|---|---|
| `uname` | 267 |
| `echo` | 235 |
| `lscpu` | 230 |
| `crontab` | 227 |
| `cat` | 225 |
| `cd` | 224 |
| `ls` | 213 |
| `top` | 213 |
| `df` | 212 |
| `free` | 212 |
| `whoami` | 211 |
| `w` | 210 |
| `INFO` | 97 |
| `canary_env` | 59 |
| `CONFIG` | 44 |


_Generated from first-party honeypot capture. CC BY 4.0._
