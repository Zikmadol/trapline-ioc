# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**696 attackers** · **138,735 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 36 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 14 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 256 |
| `ssh-bruteforce` | 204 |
| `redis-exploit` | 134 |
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
| `ssh` | 470 |
| `redis` | 139 |
| `mcp` | 58 |
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
| `root` | 247 |
| `345gs5662d34` | 205 |
| `admin` | 148 |
| `administrator` | 38 |
| `ubuntu` | 35 |
| `admin1` | 34 |
| `admin2` | 29 |
| `adminuser` | 28 |
| `AdminGPON` | 27 |
| `a` | 27 |
| `aaa` | 27 |
| `admin123` | 27 |
| `ai` | 27 |
| `agent` | 26 |
| `airflow` | 26 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 205 |
| `3245gs5662d34` | 203 |
| `123456` | 126 |
| `123` | 67 |
| `1234` | 63 |
| `admin` | 50 |
| `12345678` | 40 |
| `000000` | 39 |
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
| `uname` | 265 |
| `echo` | 233 |
| `lscpu` | 228 |
| `crontab` | 225 |
| `cat` | 224 |
| `cd` | 223 |
| `ls` | 212 |
| `top` | 212 |
| `df` | 211 |
| `free` | 211 |
| `whoami` | 210 |
| `w` | 209 |
| `INFO` | 97 |
| `canary_env` | 59 |
| `CONFIG` | 44 |


_Generated from first-party honeypot capture. CC BY 4.0._
