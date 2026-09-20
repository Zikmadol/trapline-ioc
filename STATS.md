# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**364 attackers** · **82,457 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 125 |
| `ssh-exploit` | 115 |
| `redis-exploit` | 59 |
| `mcp-abuse` | 34 |
| `llamacpp-abuse` | 7 |
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
| `ssh` | 241 |
| `redis` | 61 |
| `mcp` | 37 |
| `llamacpp` | 17 |
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
| `root` | 126 |
| `345gs5662d34` | 84 |
| `admin` | 74 |
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
| `345gs5662d34` | 84 |
| `3245gs5662d34` | 83 |
| `123456` | 71 |
| `1234` | 39 |
| `123` | 35 |
| `admin` | 32 |
| `12345678` | 32 |
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
| `uname` | 123 |
| `echo` | 96 |
| `lscpu` | 93 |
| `crontab` | 92 |
| `cat` | 87 |
| `df` | 86 |
| `whoami` | 86 |
| `ls` | 86 |
| `cd` | 86 |
| `top` | 86 |
| `w` | 85 |
| `free` | 84 |
| `INFO` | 43 |
| `canary_env` | 41 |
| `CONFIG` | 24 |


_Generated from first-party honeypot capture. CC BY 4.0._
