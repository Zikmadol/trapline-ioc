# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**620 attackers** · **134,461 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 35 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 11 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 219 |
| `ssh-bruteforce` | 194 |
| `redis-exploit` | 118 |
| `mcp-abuse` | 41 |
| `llamacpp-abuse` | 14 |
| `docker-abuse` | 7 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 420 |
| `redis` | 122 |
| `mcp` | 50 |
| `llamacpp` | 31 |
| `vllm` | 16 |
| `jupyter` | 11 |
| `docker` | 11 |
| `hfhub` | 9 |
| `ray` | 4 |
| `ollama` | 4 |
| `litellm` | 3 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 219 |
| `345gs5662d34` | 174 |
| `admin` | 135 |
| `administrator` | 35 |
| `admin1` | 31 |
| `admin2` | 29 |
| `ubuntu` | 29 |
| `AdminGPON` | 27 |
| `a` | 27 |
| `aaa` | 27 |
| `admin123` | 27 |
| `adminuser` | 27 |
| `ai` | 27 |
| `agent` | 26 |
| `Asalem` | 25 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 174 |
| `3245gs5662d34` | 172 |
| `123456` | 115 |
| `123` | 57 |
| `1234` | 55 |
| `admin` | 44 |
| `000000` | 38 |
| `12345678` | 37 |
| `12345` | 32 |
| `0000` | 30 |
| `!QAZ2wsx` | 30 |
| `123456789` | 29 |
| `0` | 29 |
| `password` | 28 |
| `00000000` | 27 |

### Top commands run

| command | times |
|---|---|
| `uname` | 231 |
| `echo` | 200 |
| `lscpu` | 196 |
| `crontab` | 194 |
| `cat` | 189 |
| `cd` | 187 |
| `ls` | 180 |
| `top` | 180 |
| `df` | 179 |
| `whoami` | 179 |
| `free` | 178 |
| `w` | 178 |
| `INFO` | 85 |
| `canary_env` | 51 |
| `CONFIG` | 41 |


_Generated from first-party honeypot capture. CC BY 4.0._
