# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**559 attackers** · **117,848 hostile actions** · covering 10 day(s) through 2026-09-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 32 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 8 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 194 |
| `ssh-bruteforce` | 188 |
| `redis-exploit` | 98 |
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
| `ssh` | 388 |
| `redis` | 100 |
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
| `root` | 202 |
| `345gs5662d34` | 152 |
| `admin` | 130 |
| `administrator` | 33 |
| `admin1` | 30 |
| `admin2` | 28 |
| `ubuntu` | 28 |
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
| `345gs5662d34` | 152 |
| `3245gs5662d34` | 150 |
| `123456` | 105 |
| `123` | 55 |
| `1234` | 53 |
| `admin` | 42 |
| `000000` | 37 |
| `12345678` | 35 |
| `12345` | 32 |
| `123456789` | 29 |
| `0000` | 29 |
| `!QAZ2wsx` | 29 |
| `0` | 28 |
| `password` | 26 |
| `00000000` | 26 |

### Top commands run

| command | times |
|---|---|
| `uname` | 206 |
| `echo` | 176 |
| `lscpu` | 172 |
| `crontab` | 170 |
| `cat` | 165 |
| `cd` | 163 |
| `ls` | 158 |
| `top` | 158 |
| `df` | 157 |
| `whoami` | 157 |
| `free` | 156 |
| `w` | 156 |
| `INFO` | 72 |
| `canary_env` | 47 |
| `CONFIG` | 40 |


_Generated from first-party honeypot capture. CC BY 4.0._
