# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**486 attackers** · **103,506 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 30 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 7 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 164 |
| `ssh-bruteforce` | 158 |
| `redis-exploit` | 89 |
| `mcp-abuse` | 37 |
| `llamacpp-abuse` | 11 |
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
| `ssh` | 327 |
| `redis` | 91 |
| `mcp` | 41 |
| `llamacpp` | 23 |
| `vllm` | 14 |
| `jupyter` | 10 |
| `docker` | 6 |
| `hfhub` | 5 |
| `ray` | 4 |
| `litellm` | 3 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 180 |
| `345gs5662d34` | 132 |
| `admin` | 95 |
| `administrator` | 31 |
| `admin1` | 28 |
| `admin2` | 25 |
| `a` | 24 |
| `adminuser` | 24 |
| `ai` | 24 |
| `AdminGPON` | 23 |
| `aaa` | 23 |
| `admin123` | 23 |
| `Asalem` | 22 |
| `abigail` | 22 |
| `admin1234` | 22 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 132 |
| `3245gs5662d34` | 131 |
| `123456` | 95 |
| `123` | 48 |
| `1234` | 46 |
| `admin` | 40 |
| `12345678` | 35 |
| `000000` | 34 |
| `12345` | 32 |
| `123456789` | 29 |
| `!QAZ2wsx` | 27 |
| `0000` | 26 |
| `0` | 26 |
| `!Q2w3e4r` | 23 |
| `!Q@W3e4r` | 23 |

### Top commands run

| command | times |
|---|---|
| `uname` | 176 |
| `echo` | 151 |
| `lscpu` | 148 |
| `crontab` | 146 |
| `ls` | 136 |
| `cd` | 136 |
| `cat` | 136 |
| `top` | 136 |
| `df` | 135 |
| `w` | 135 |
| `whoami` | 135 |
| `free` | 134 |
| `INFO` | 66 |
| `canary_env` | 45 |
| `CONFIG` | 37 |


_Generated from first-party honeypot capture. CC BY 4.0._
