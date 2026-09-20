# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**389 attackers** · **88,776 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 28 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 131 |
| `ssh-exploit` | 124 |
| `redis-exploit` | 67 |
| `mcp-abuse` | 34 |
| `llamacpp-abuse` | 9 |
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
| `ssh` | 256 |
| `redis` | 69 |
| `mcp` | 37 |
| `llamacpp` | 20 |
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
| `root` | 136 |
| `345gs5662d34` | 92 |
| `admin` | 77 |
| `administrator` | 28 |
| `admin1` | 24 |
| `admin2` | 23 |
| `AdminGPON` | 21 |
| `a` | 21 |
| `aaa` | 21 |
| `admin123` | 21 |
| `adminuser` | 21 |
| `ai` | 21 |
| `Asalem` | 19 |
| `Caps` | 19 |
| `abigail` | 19 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 92 |
| `3245gs5662d34` | 91 |
| `123456` | 74 |
| `1234` | 39 |
| `123` | 37 |
| `12345678` | 33 |
| `admin` | 32 |
| `000000` | 30 |
| `12345` | 30 |
| `123456789` | 28 |
| `!QAZ2wsx` | 24 |
| `0000` | 23 |
| `0` | 23 |
| `123123` | 21 |
| `1234567` | 21 |

### Top commands run

| command | times |
|---|---|
| `uname` | 132 |
| `echo` | 106 |
| `lscpu` | 102 |
| `crontab` | 101 |
| `cat` | 95 |
| `df` | 94 |
| `whoami` | 94 |
| `ls` | 94 |
| `cd` | 94 |
| `top` | 94 |
| `w` | 93 |
| `free` | 92 |
| `INFO` | 50 |
| `canary_env` | 42 |
| `CONFIG` | 27 |


_Generated from first-party honeypot capture. CC BY 4.0._
