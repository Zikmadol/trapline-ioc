# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**575 attackers** · **123,236 hostile actions** · covering 10 day(s) through 2026-09-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 34 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 8 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 198 |
| `ssh-bruteforce` | 188 |
| `redis-exploit` | 105 |
| `mcp-abuse` | 39 |
| `llamacpp-abuse` | 12 |
| `docker-abuse` | 6 |
| `vllm-abuse` | 4 |
| `ollama-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `llamacpp-key-replay` | 1 |
| `jupyter-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 392 |
| `redis` | 107 |
| `mcp` | 46 |
| `llamacpp` | 27 |
| `vllm` | 16 |
| `jupyter` | 11 |
| `docker` | 9 |
| `hfhub` | 8 |
| `ray` | 4 |
| `litellm` | 3 |
| `ollama` | 3 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 204 |
| `345gs5662d34` | 155 |
| `admin` | 130 |
| `administrator` | 34 |
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
| `345gs5662d34` | 155 |
| `3245gs5662d34` | 153 |
| `123456` | 105 |
| `123` | 55 |
| `1234` | 54 |
| `admin` | 42 |
| `000000` | 37 |
| `12345678` | 36 |
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
| `uname` | 209 |
| `echo` | 180 |
| `lscpu` | 176 |
| `crontab` | 174 |
| `cat` | 168 |
| `cd` | 166 |
| `ls` | 161 |
| `top` | 161 |
| `df` | 160 |
| `whoami` | 160 |
| `free` | 159 |
| `w` | 159 |
| `INFO` | 78 |
| `canary_env` | 48 |
| `CONFIG` | 41 |


_Generated from first-party honeypot capture. CC BY 4.0._
