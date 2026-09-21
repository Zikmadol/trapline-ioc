# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**482 attackers** · **101,415 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 29 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 6 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 162 |
| `ssh-bruteforce` | 158 |
| `redis-exploit` | 87 |
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
| `ssh` | 324 |
| `redis` | 89 |
| `mcp` | 41 |
| `llamacpp` | 22 |
| `vllm` | 14 |
| `jupyter` | 10 |
| `docker` | 6 |
| `hfhub` | 4 |
| `ray` | 4 |
| `litellm` | 3 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 178 |
| `345gs5662d34` | 130 |
| `admin` | 94 |
| `administrator` | 30 |
| `admin1` | 27 |
| `admin2` | 25 |
| `AdminGPON` | 23 |
| `a` | 23 |
| `aaa` | 23 |
| `admin123` | 23 |
| `adminuser` | 23 |
| `ai` | 23 |
| `Asalem` | 21 |
| `Caps` | 21 |
| `abigail` | 21 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 130 |
| `3245gs5662d34` | 129 |
| `123456` | 95 |
| `123` | 47 |
| `1234` | 45 |
| `admin` | 40 |
| `12345678` | 35 |
| `000000` | 34 |
| `12345` | 31 |
| `123456789` | 29 |
| `!QAZ2wsx` | 26 |
| `0000` | 25 |
| `0` | 25 |
| `00000000` | 23 |
| `051178` | 23 |

### Top commands run

| command | times |
|---|---|
| `uname` | 173 |
| `echo` | 148 |
| `lscpu` | 145 |
| `crontab` | 143 |
| `ls` | 134 |
| `cd` | 134 |
| `cat` | 134 |
| `top` | 134 |
| `df` | 133 |
| `w` | 133 |
| `whoami` | 133 |
| `free` | 132 |
| `INFO` | 64 |
| `canary_env` | 45 |
| `CONFIG` | 36 |


_Generated from first-party honeypot capture. CC BY 4.0._
