# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**542 attackers** · **117,234 hostile actions** · covering 10 day(s) through 2026-09-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 32 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 7 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 186 |
| `ssh-exploit` | 184 |
| `redis-exploit` | 94 |
| `mcp-abuse` | 37 |
| `llamacpp-abuse` | 12 |
| `docker-abuse` | 4 |
| `vllm-abuse` | 3 |
| `jupyter-abuse` | 1 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |
| `ollama-abuse` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 375 |
| `redis` | 96 |
| `mcp` | 43 |
| `llamacpp` | 26 |
| `vllm` | 14 |
| `jupyter` | 10 |
| `docker` | 7 |
| `hfhub` | 5 |
| `ray` | 4 |
| `litellm` | 3 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 196 |
| `345gs5662d34` | 146 |
| `admin` | 125 |
| `administrator` | 33 |
| `admin1` | 30 |
| `admin2` | 28 |
| `AdminGPON` | 26 |
| `a` | 26 |
| `aaa` | 26 |
| `admin123` | 26 |
| `adminuser` | 26 |
| `ai` | 26 |
| `ubuntu` | 25 |
| `Asalem` | 24 |
| `Caps` | 24 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 146 |
| `3245gs5662d34` | 145 |
| `123456` | 102 |
| `123` | 52 |
| `1234` | 50 |
| `admin` | 40 |
| `000000` | 37 |
| `12345678` | 35 |
| `12345` | 32 |
| `123456789` | 29 |
| `0000` | 29 |
| `!QAZ2wsx` | 29 |
| `0` | 28 |
| `00000000` | 26 |
| `051178` | 26 |

### Top commands run

| command | times |
|---|---|
| `uname` | 196 |
| `echo` | 169 |
| `lscpu` | 165 |
| `crontab` | 163 |
| `cat` | 155 |
| `cd` | 153 |
| `ls` | 151 |
| `top` | 151 |
| `df` | 150 |
| `w` | 150 |
| `whoami` | 150 |
| `free` | 149 |
| `INFO` | 70 |
| `canary_env` | 46 |
| `CONFIG` | 39 |


_Generated from first-party honeypot capture. CC BY 4.0._
