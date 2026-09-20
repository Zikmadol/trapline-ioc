# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**397 attackers** · **89,122 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 4 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 132 |
| `ssh-exploit` | 129 |
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
| `ssh` | 262 |
| `redis` | 69 |
| `mcp` | 36 |
| `llamacpp` | 19 |
| `vllm` | 10 |
| `jupyter` | 7 |
| `ray` | 4 |
| `docker` | 4 |
| `hfhub` | 3 |
| `litellm` | 3 |
| `ollama` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 140 |
| `345gs5662d34` | 98 |
| `admin` | 78 |
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
| `admin` | 33 |
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
| `uname` | 137 |
| `echo` | 112 |
| `crontab` | 107 |
| `lscpu` | 107 |
| `ls` | 100 |
| `cd` | 100 |
| `cat` | 100 |
| `top` | 100 |
| `df` | 99 |
| `w` | 99 |
| `whoami` | 99 |
| `free` | 98 |
| `INFO` | 50 |
| `canary_env` | 41 |
| `CONFIG` | 27 |


_Generated from first-party honeypot capture. CC BY 4.0._
