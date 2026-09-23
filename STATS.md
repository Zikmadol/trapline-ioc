# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**611 attackers** · **134,161 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 35 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 10 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 217 |
| `ssh-bruteforce` | 191 |
| `redis-exploit` | 116 |
| `mcp-abuse` | 41 |
| `llamacpp-abuse` | 13 |
| `docker-abuse` | 6 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 415 |
| `redis` | 119 |
| `mcp` | 50 |
| `llamacpp` | 29 |
| `vllm` | 16 |
| `jupyter` | 11 |
| `docker` | 10 |
| `hfhub` | 8 |
| `ray` | 4 |
| `ollama` | 4 |
| `litellm` | 3 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 216 |
| `345gs5662d34` | 171 |
| `admin` | 134 |
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
| `Asalem` | 25 |
| `Caps` | 25 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 171 |
| `3245gs5662d34` | 169 |
| `123456` | 113 |
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
| `password` | 27 |
| `00000000` | 27 |

### Top commands run

| command | times |
|---|---|
| `uname` | 228 |
| `echo` | 197 |
| `lscpu` | 193 |
| `crontab` | 191 |
| `cat` | 186 |
| `cd` | 184 |
| `ls` | 177 |
| `top` | 177 |
| `df` | 176 |
| `whoami` | 176 |
| `free` | 175 |
| `w` | 175 |
| `INFO` | 83 |
| `canary_env` | 51 |
| `CONFIG` | 41 |


_Generated from first-party honeypot capture. CC BY 4.0._
