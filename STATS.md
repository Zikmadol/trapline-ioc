# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**362 attackers** · **82,150 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 128 |
| `ssh-exploit` | 111 |
| `redis-exploit` | 59 |
| `mcp-abuse` | 34 |
| `llamacpp-abuse` | 6 |
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
| `ssh` | 240 |
| `redis` | 60 |
| `mcp` | 37 |
| `llamacpp` | 16 |
| `vllm` | 11 |
| `jupyter` | 8 |
| `docker` | 4 |
| `hfhub` | 4 |
| `litellm` | 4 |
| `ray` | 4 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 123 |
| `345gs5662d34` | 80 |
| `admin` | 73 |
| `administrator` | 26 |
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
| `345gs5662d34` | 80 |
| `3245gs5662d34` | 79 |
| `123456` | 69 |
| `1234` | 37 |
| `123` | 35 |
| `admin` | 33 |
| `12345678` | 31 |
| `000000` | 29 |
| `12345` | 28 |
| `123456789` | 28 |
| `!QAZ2wsx` | 23 |
| `0000` | 22 |
| `123123` | 21 |
| `1234567` | 21 |
| `0` | 21 |

### Top commands run

| command | times |
|---|---|
| `uname` | 119 |
| `echo` | 92 |
| `lscpu` | 89 |
| `crontab` | 89 |
| `cat` | 83 |
| `ls` | 83 |
| `df` | 82 |
| `whoami` | 82 |
| `cd` | 82 |
| `top` | 82 |
| `w` | 82 |
| `free` | 81 |
| `INFO` | 43 |
| `canary_env` | 40 |
| `CONFIG` | 24 |


_Generated from first-party honeypot capture. CC BY 4.0._
