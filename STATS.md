# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**647 attackers** · **136,179 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 35 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 12 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 233 |
| `ssh-bruteforce` | 196 |
| `redis-exploit` | 123 |
| `mcp-abuse` | 44 |
| `llamacpp-abuse` | 14 |
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
| `ssh` | 437 |
| `redis` | 127 |
| `mcp` | 54 |
| `llamacpp` | 32 |
| `vllm` | 18 |
| `jupyter` | 14 |
| `docker` | 11 |
| `hfhub` | 10 |
| `ollama` | 6 |
| `litellm` | 4 |
| `ray` | 4 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 227 |
| `345gs5662d34` | 184 |
| `admin` | 141 |
| `administrator` | 37 |
| `admin1` | 32 |
| `ubuntu` | 31 |
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
| `345gs5662d34` | 184 |
| `3245gs5662d34` | 183 |
| `123456` | 119 |
| `123` | 60 |
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
| `uname` | 244 |
| `echo` | 211 |
| `lscpu` | 207 |
| `crontab` | 205 |
| `cat` | 202 |
| `cd` | 201 |
| `ls` | 191 |
| `top` | 191 |
| `df` | 190 |
| `whoami` | 190 |
| `free` | 189 |
| `w` | 189 |
| `INFO` | 88 |
| `canary_env` | 55 |
| `CONFIG` | 42 |


_Generated from first-party honeypot capture. CC BY 4.0._
