# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**637 attackers** · **135,133 hostile actions** · covering 11 day(s) through 2026-09-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 35 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 12 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 228 |
| `ssh-bruteforce` | 194 |
| `redis-exploit` | 123 |
| `mcp-abuse` | 42 |
| `llamacpp-abuse` | 14 |
| `docker-abuse` | 7 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 3 |
| `jupyter-abuse` | 2 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 430 |
| `redis` | 127 |
| `mcp` | 51 |
| `llamacpp` | 31 |
| `vllm` | 18 |
| `jupyter` | 13 |
| `docker` | 11 |
| `hfhub` | 10 |
| `ollama` | 5 |
| `litellm` | 4 |
| `ray` | 4 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 222 |
| `345gs5662d34` | 179 |
| `admin` | 138 |
| `administrator` | 36 |
| `admin1` | 31 |
| `ubuntu` | 30 |
| `admin2` | 29 |
| `AdminGPON` | 27 |
| `a` | 27 |
| `aaa` | 27 |
| `admin123` | 27 |
| `adminuser` | 27 |
| `ai` | 27 |
| `agent` | 26 |
| `Asalem` | 25 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 179 |
| `3245gs5662d34` | 178 |
| `123456` | 116 |
| `123` | 60 |
| `1234` | 57 |
| `admin` | 47 |
| `000000` | 38 |
| `12345678` | 37 |
| `12345` | 32 |
| `0000` | 30 |
| `!QAZ2wsx` | 30 |
| `123456789` | 29 |
| `0` | 29 |
| `password` | 28 |
| `00000000` | 27 |

### Top commands run

| command | times |
|---|---|
| `uname` | 239 |
| `echo` | 206 |
| `lscpu` | 202 |
| `crontab` | 200 |
| `cat` | 197 |
| `cd` | 196 |
| `ls` | 186 |
| `top` | 186 |
| `df` | 185 |
| `whoami` | 185 |
| `free` | 184 |
| `w` | 184 |
| `INFO` | 88 |
| `canary_env` | 53 |
| `CONFIG` | 42 |


_Generated from first-party honeypot capture. CC BY 4.0._
