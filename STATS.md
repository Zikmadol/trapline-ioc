# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**352 attackers** · **81,316 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 147 |
| `ssh-exploit` | 86 |
| `redis-exploit` | 57 |
| `mcp-abuse` | 32 |
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
| `ssh` | 234 |
| `redis` | 58 |
| `mcp` | 35 |
| `llamacpp` | 15 |
| `vllm` | 10 |
| `jupyter` | 7 |
| `docker` | 4 |
| `litellm` | 4 |
| `ray` | 4 |
| `hfhub` | 3 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 116 |
| `admin` | 72 |
| `345gs5662d34` | 55 |
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
| `345gs5662d34` | 55 |
| `3245gs5662d34` | 54 |
| `123456` | 53 |
| `1234` | 37 |
| `admin` | 32 |
| `123` | 31 |
| `12345678` | 31 |
| `000000` | 29 |
| `123456789` | 28 |
| `12345` | 25 |
| `!QAZ2wsx` | 23 |
| `0000` | 22 |
| `0` | 21 |
| `123123` | 20 |
| `00000000` | 20 |

### Top commands run

| command | times |
|---|---|
| `uname` | 93 |
| `echo` | 67 |
| `lscpu` | 63 |
| `crontab` | 63 |
| `cat` | 58 |
| `ls` | 57 |
| `cd` | 57 |
| `df` | 56 |
| `whoami` | 56 |
| `top` | 56 |
| `w` | 56 |
| `free` | 55 |
| `INFO` | 42 |
| `canary_env` | 38 |
| `CONFIG` | 23 |


_Generated from first-party honeypot capture. CC BY 4.0._
