# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**478 attackers** · **98,016 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 29 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 6 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 159 |
| `ssh-bruteforce` | 158 |
| `redis-exploit` | 87 |
| `mcp-abuse` | 37 |
| `llamacpp-abuse` | 10 |
| `vllm-abuse` | 3 |
| `docker-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 321 |
| `redis` | 89 |
| `mcp` | 41 |
| `llamacpp` | 21 |
| `vllm` | 13 |
| `jupyter` | 10 |
| `docker` | 6 |
| `hfhub` | 4 |
| `ray` | 4 |
| `litellm` | 3 |
| `ollama` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 178 |
| `345gs5662d34` | 127 |
| `admin` | 94 |
| `administrator` | 30 |
| `admin1` | 26 |
| `admin2` | 24 |
| `AdminGPON` | 23 |
| `admin123` | 23 |
| `adminuser` | 23 |
| `ai` | 23 |
| `a` | 22 |
| `aaa` | 22 |
| `Asalem` | 21 |
| `abigail` | 21 |
| `Caps` | 20 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 127 |
| `3245gs5662d34` | 126 |
| `123456` | 93 |
| `123` | 48 |
| `1234` | 45 |
| `admin` | 40 |
| `12345678` | 36 |
| `000000` | 34 |
| `12345` | 32 |
| `123456789` | 30 |
| `!QAZ2wsx` | 25 |
| `0000` | 24 |
| `0` | 24 |
| `password` | 22 |
| `123123` | 22 |

### Top commands run

| command | times |
|---|---|
| `uname` | 170 |
| `echo` | 145 |
| `lscpu` | 142 |
| `crontab` | 140 |
| `ls` | 131 |
| `cd` | 131 |
| `cat` | 131 |
| `top` | 131 |
| `df` | 130 |
| `w` | 130 |
| `whoami` | 130 |
| `free` | 129 |
| `INFO` | 64 |
| `canary_env` | 45 |
| `CONFIG` | 36 |


_Generated from first-party honeypot capture. CC BY 4.0._
