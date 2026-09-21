# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**471 attackers** · **96,564 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 28 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 6 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 157 |
| `ssh-exploit` | 154 |
| `redis-exploit` | 86 |
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
| `ssh` | 315 |
| `redis` | 88 |
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
| `root` | 175 |
| `345gs5662d34` | 123 |
| `admin` | 93 |
| `administrator` | 29 |
| `admin1` | 26 |
| `admin2` | 24 |
| `AdminGPON` | 22 |
| `a` | 22 |
| `aaa` | 22 |
| `admin123` | 22 |
| `adminuser` | 22 |
| `ai` | 22 |
| `Asalem` | 20 |
| `Caps` | 20 |
| `abigail` | 20 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 123 |
| `3245gs5662d34` | 122 |
| `123456` | 91 |
| `123` | 46 |
| `1234` | 44 |
| `admin` | 40 |
| `12345678` | 35 |
| `000000` | 33 |
| `12345` | 31 |
| `123456789` | 29 |
| `!QAZ2wsx` | 25 |
| `0000` | 24 |
| `0` | 24 |
| `1234567` | 22 |
| `00000000` | 22 |

### Top commands run

| command | times |
|---|---|
| `uname` | 165 |
| `echo` | 140 |
| `lscpu` | 137 |
| `crontab` | 135 |
| `ls` | 127 |
| `cd` | 127 |
| `cat` | 127 |
| `top` | 127 |
| `df` | 126 |
| `w` | 126 |
| `whoami` | 126 |
| `free` | 125 |
| `INFO` | 63 |
| `canary_env` | 45 |
| `CONFIG` | 35 |


_Generated from first-party honeypot capture. CC BY 4.0._
