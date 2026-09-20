# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**394 attackers** · **88,902 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 4 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 134 |
| `ssh-exploit` | 126 |
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
| `ssh` | 261 |
| `redis` | 68 |
| `mcp` | 36 |
| `llamacpp` | 19 |
| `vllm` | 10 |
| `jupyter` | 7 |
| `ray` | 4 |
| `hfhub` | 3 |
| `litellm` | 3 |
| `docker` | 3 |
| `ollama` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 140 |
| `345gs5662d34` | 96 |
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
| `345gs5662d34` | 96 |
| `3245gs5662d34` | 95 |
| `123456` | 73 |
| `123` | 41 |
| `1234` | 39 |
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
| `uname` | 134 |
| `echo` | 109 |
| `crontab` | 104 |
| `lscpu` | 104 |
| `cd` | 98 |
| `cat` | 98 |
| `ls` | 97 |
| `top` | 97 |
| `df` | 96 |
| `w` | 96 |
| `whoami` | 96 |
| `free` | 95 |
| `INFO` | 49 |
| `canary_env` | 41 |
| `CONFIG` | 27 |


_Generated from first-party honeypot capture. CC BY 4.0._
