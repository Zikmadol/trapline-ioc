# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**417 attackers** · **93,861 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 28 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 4 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 141 |
| `ssh-exploit` | 139 |
| `redis-exploit` | 69 |
| `mcp-abuse` | 34 |
| `llamacpp-abuse` | 9 |
| `llamacpp-key-replay` | 2 |
| `vllm-abuse` | 2 |
| `docker-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 281 |
| `redis` | 70 |
| `mcp` | 37 |
| `llamacpp` | 19 |
| `vllm` | 11 |
| `jupyter` | 7 |
| `ray` | 4 |
| `docker` | 4 |
| `hfhub` | 3 |
| `litellm` | 3 |
| `ollama` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 153 |
| `345gs5662d34` | 109 |
| `admin` | 85 |
| `administrator` | 29 |
| `admin1` | 25 |
| `admin2` | 24 |
| `AdminGPON` | 22 |
| `a` | 22 |
| `aaa` | 22 |
| `admin123` | 22 |
| `adminuser` | 22 |
| `ai` | 22 |
| `Asalem` | 20 |
| `Caps` | 20 |
| `abigail` | 20 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 109 |
| `3245gs5662d34` | 108 |
| `123456` | 81 |
| `123` | 43 |
| `1234` | 39 |
| `admin` | 36 |
| `000000` | 33 |
| `12345678` | 33 |
| `12345` | 30 |
| `123456789` | 28 |
| `!QAZ2wsx` | 25 |
| `0000` | 24 |
| `0` | 24 |
| `051178` | 22 |
| `123123` | 21 |

### Top commands run

| command | times |
|---|---|
| `uname` | 150 |
| `echo` | 125 |
| `lscpu` | 121 |
| `crontab` | 120 |
| `ls` | 112 |
| `cd` | 112 |
| `cat` | 112 |
| `top` | 112 |
| `df` | 111 |
| `w` | 111 |
| `whoami` | 111 |
| `free` | 110 |
| `INFO` | 51 |
| `canary_env` | 41 |
| `CONFIG` | 28 |


_Generated from first-party honeypot capture. CC BY 4.0._
