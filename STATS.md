# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**401 attackers** · **89,164 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 4 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 135 |
| `ssh-exploit` | 130 |
| `redis-exploit` | 68 |
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
| `ssh` | 266 |
| `redis` | 69 |
| `mcp` | 36 |
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
| `root` | 144 |
| `345gs5662d34` | 98 |
| `admin` | 79 |
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
| `345gs5662d34` | 98 |
| `3245gs5662d34` | 97 |
| `123456` | 75 |
| `123` | 41 |
| `1234` | 39 |
| `admin` | 34 |
| `12345678` | 33 |
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
| `uname` | 138 |
| `echo` | 113 |
| `crontab` | 108 |
| `lscpu` | 108 |
| `ls` | 101 |
| `cd` | 101 |
| `cat` | 101 |
| `top` | 101 |
| `df` | 100 |
| `w` | 100 |
| `whoami` | 100 |
| `free` | 99 |
| `INFO` | 50 |
| `canary_env` | 41 |
| `CONFIG` | 27 |


_Generated from first-party honeypot capture. CC BY 4.0._
