# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**294 attackers** · **80,472 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 122 |
| `redis-exploit` | 57 |
| `ssh-exploit` | 54 |
| `mcp-abuse` | 31 |
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
| `ssh` | 177 |
| `redis` | 58 |
| `mcp` | 34 |
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
| `root` | 86 |
| `admin` | 72 |
| `administrator` | 26 |
| `345gs5662d34` | 24 |
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
| `123456` | 40 |
| `1234` | 33 |
| `admin` | 32 |
| `12345678` | 30 |
| `000000` | 29 |
| `123456789` | 28 |
| `12345` | 24 |
| `3245gs5662d34` | 24 |
| `345gs5662d34` | 24 |
| `123` | 23 |
| `!QAZ2wsx` | 23 |
| `0000` | 22 |
| `0` | 21 |
| `00000000` | 20 |
| `051178` | 20 |

### Top commands run

| command | times |
|---|---|
| `uname` | 62 |
| `INFO` | 42 |
| `canary_env` | 37 |
| `echo` | 35 |
| `lscpu` | 32 |
| `crontab` | 32 |
| `cat` | 26 |
| `ls` | 26 |
| `df` | 25 |
| `whoami` | 25 |
| `cd` | 25 |
| `top` | 25 |
| `w` | 25 |
| `free` | 24 |
| `CONFIG` | 23 |


_Generated from first-party honeypot capture. CC BY 4.0._
