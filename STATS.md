# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**380 attackers** · **83,663 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 130 |
| `ssh-exploit` | 119 |
| `redis-exploit` | 64 |
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
| `ssh` | 250 |
| `redis` | 66 |
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
| `root` | 131 |
| `345gs5662d34` | 88 |
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
| `345gs5662d34` | 88 |
| `3245gs5662d34` | 87 |
| `123456` | 72 |
| `1234` | 39 |
| `123` | 35 |
| `12345678` | 33 |
| `admin` | 32 |
| `12345` | 30 |
| `000000` | 29 |
| `123456789` | 28 |
| `!QAZ2wsx` | 23 |
| `0000` | 22 |
| `123123` | 21 |
| `1234567` | 21 |
| `0` | 21 |

### Top commands run

| command | times |
|---|---|
| `uname` | 127 |
| `echo` | 100 |
| `lscpu` | 97 |
| `crontab` | 96 |
| `cat` | 91 |
| `df` | 90 |
| `whoami` | 90 |
| `ls` | 90 |
| `cd` | 90 |
| `top` | 90 |
| `w` | 89 |
| `free` | 88 |
| `INFO` | 47 |
| `canary_env` | 42 |
| `CONFIG` | 26 |


_Generated from first-party honeypot capture. CC BY 4.0._
