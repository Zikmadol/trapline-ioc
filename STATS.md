# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**657 attackers** · **136,622 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 36 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 12 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 237 |
| `ssh-bruteforce` | 197 |
| `redis-exploit` | 127 |
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
| `ssh` | 442 |
| `redis` | 132 |
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
| `root` | 230 |
| `345gs5662d34` | 187 |
| `admin` | 142 |
| `administrator` | 37 |
| `admin1` | 32 |
| `ubuntu` | 32 |
| `admin2` | 29 |
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
| `345gs5662d34` | 187 |
| `3245gs5662d34` | 186 |
| `123456` | 122 |
| `123` | 62 |
| `1234` | 58 |
| `admin` | 49 |
| `000000` | 39 |
| `12345678` | 37 |
| `12345` | 33 |
| `0000` | 30 |
| `!QAZ2wsx` | 30 |
| `123456789` | 29 |
| `0` | 29 |
| `password` | 27 |
| `00000000` | 27 |

### Top commands run

| command | times |
|---|---|
| `uname` | 247 |
| `echo` | 214 |
| `lscpu` | 210 |
| `crontab` | 208 |
| `cat` | 205 |
| `cd` | 204 |
| `ls` | 194 |
| `top` | 194 |
| `df` | 193 |
| `whoami` | 193 |
| `free` | 192 |
| `w` | 192 |
| `INFO` | 91 |
| `canary_env` | 56 |
| `CONFIG` | 42 |


_Generated from first-party honeypot capture. CC BY 4.0._
