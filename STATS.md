# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**606 attackers** · **134,012 hostile actions** · covering 10 day(s) through 2026-09-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 35 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 10 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 216 |
| `ssh-bruteforce` | 190 |
| `redis-exploit` | 114 |
| `mcp-abuse` | 40 |
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
| `ssh` | 413 |
| `redis` | 117 |
| `mcp` | 47 |
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
| `root` | 214 |
| `345gs5662d34` | 170 |
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
| `345gs5662d34` | 170 |
| `3245gs5662d34` | 168 |
| `123456` | 112 |
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
| `uname` | 227 |
| `echo` | 196 |
| `lscpu` | 192 |
| `crontab` | 190 |
| `cat` | 185 |
| `cd` | 183 |
| `ls` | 176 |
| `top` | 176 |
| `df` | 175 |
| `whoami` | 175 |
| `free` | 174 |
| `w` | 174 |
| `INFO` | 83 |
| `canary_env` | 50 |
| `CONFIG` | 41 |


_Generated from first-party honeypot capture. CC BY 4.0._
