# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**552 attackers** · **117,404 hostile actions** · covering 10 day(s) through 2026-09-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 32 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 8 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 192 |
| `ssh-exploit` | 185 |
| `redis-exploit` | 96 |
| `mcp-abuse` | 38 |
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
| `ssh` | 383 |
| `redis` | 98 |
| `mcp` | 44 |
| `llamacpp` | 26 |
| `vllm` | 14 |
| `jupyter` | 10 |
| `docker` | 7 |
| `hfhub` | 6 |
| `ray` | 4 |
| `litellm` | 3 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 199 |
| `345gs5662d34` | 146 |
| `admin` | 128 |
| `administrator` | 33 |
| `admin1` | 30 |
| `admin2` | 28 |
| `ubuntu` | 27 |
| `AdminGPON` | 26 |
| `a` | 26 |
| `aaa` | 26 |
| `admin123` | 26 |
| `adminuser` | 26 |
| `ai` | 26 |
| `Asalem` | 24 |
| `Caps` | 24 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 146 |
| `3245gs5662d34` | 145 |
| `123456` | 102 |
| `123` | 53 |
| `1234` | 50 |
| `admin` | 41 |
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
| `uname` | 197 |
| `echo` | 169 |
| `lscpu` | 165 |
| `crontab` | 163 |
| `cat` | 156 |
| `cd` | 154 |
| `ls` | 151 |
| `top` | 151 |
| `df` | 150 |
| `w` | 150 |
| `whoami` | 150 |
| `free` | 149 |
| `INFO` | 71 |
| `canary_env` | 47 |
| `CONFIG` | 39 |


_Generated from first-party honeypot capture. CC BY 4.0._
