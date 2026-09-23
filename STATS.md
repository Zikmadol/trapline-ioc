# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**631 attackers** · **134,862 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 35 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 12 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 227 |
| `ssh-bruteforce` | 193 |
| `redis-exploit` | 120 |
| `mcp-abuse` | 42 |
| `llamacpp-abuse` | 14 |
| `docker-abuse` | 7 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 3 |
| `jupyter-abuse` | 1 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 428 |
| `redis` | 124 |
| `mcp` | 51 |
| `llamacpp` | 31 |
| `vllm` | 17 |
| `jupyter` | 12 |
| `docker` | 11 |
| `hfhub` | 9 |
| `ollama` | 5 |
| `litellm` | 4 |
| `ray` | 4 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 221 |
| `345gs5662d34` | 178 |
| `admin` | 137 |
| `administrator` | 36 |
| `admin1` | 31 |
| `ubuntu` | 30 |
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
| `345gs5662d34` | 178 |
| `3245gs5662d34` | 177 |
| `123456` | 116 |
| `123` | 60 |
| `1234` | 57 |
| `admin` | 45 |
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
| `uname` | 238 |
| `echo` | 205 |
| `lscpu` | 201 |
| `crontab` | 199 |
| `cat` | 196 |
| `cd` | 195 |
| `ls` | 185 |
| `top` | 185 |
| `df` | 184 |
| `whoami` | 184 |
| `free` | 183 |
| `w` | 183 |
| `INFO` | 86 |
| `canary_env` | 52 |
| `CONFIG` | 41 |


_Generated from first-party honeypot capture. CC BY 4.0._
