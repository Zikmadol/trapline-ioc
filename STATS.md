# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**371 attackers** · **82,685 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 127 |
| `ssh-exploit` | 116 |
| `redis-exploit` | 62 |
| `mcp-abuse` | 34 |
| `llamacpp-abuse` | 8 |
| `llamacpp-key-replay` | 2 |
| `vllm-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |
| `docker-abuse` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 244 |
| `redis` | 64 |
| `mcp` | 37 |
| `llamacpp` | 19 |
| `vllm` | 11 |
| `jupyter` | 8 |
| `ray` | 5 |
| `docker` | 4 |
| `hfhub` | 4 |
| `litellm` | 4 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 129 |
| `345gs5662d34` | 85 |
| `admin` | 76 |
| `administrator` | 27 |
| `admin1` | 23 |
| `admin2` | 22 |
| `AdminGPON` | 20 |
| `a` | 20 |
| `aaa` | 20 |
| `admin123` | 20 |
| `adminuser` | 20 |
| `ai` | 20 |
| `Asalem` | 18 |
| `Caps` | 18 |
| `abigail` | 18 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 85 |
| `3245gs5662d34` | 84 |
| `123456` | 71 |
| `1234` | 39 |
| `123` | 35 |
| `admin` | 32 |
| `12345678` | 32 |
| `000000` | 29 |
| `12345` | 29 |
| `123456789` | 28 |
| `!QAZ2wsx` | 23 |
| `0000` | 22 |
| `123123` | 21 |
| `1234567` | 21 |
| `0` | 21 |

### Top commands run

| command | times |
|---|---|
| `uname` | 124 |
| `echo` | 97 |
| `lscpu` | 94 |
| `crontab` | 93 |
| `cat` | 88 |
| `df` | 87 |
| `whoami` | 87 |
| `ls` | 87 |
| `cd` | 87 |
| `top` | 87 |
| `w` | 86 |
| `free` | 85 |
| `INFO` | 46 |
| `canary_env` | 41 |
| `CONFIG` | 25 |


_Generated from first-party honeypot capture. CC BY 4.0._
