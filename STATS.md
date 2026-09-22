# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**578 attackers** · **123,434 hostile actions** · covering 10 day(s) through 2026-09-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 34 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 8 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 201 |
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
| `ssh` | 395 |
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
| `root` | 206 |
| `345gs5662d34` | 158 |
| `admin` | 131 |
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
| `345gs5662d34` | 158 |
| `3245gs5662d34` | 156 |
| `123456` | 106 |
| `123` | 55 |
| `1234` | 55 |
| `admin` | 43 |
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
| `uname` | 212 |
| `echo` | 183 |
| `lscpu` | 179 |
| `crontab` | 177 |
| `cat` | 171 |
| `cd` | 169 |
| `ls` | 164 |
| `top` | 164 |
| `df` | 163 |
| `whoami` | 163 |
| `free` | 162 |
| `w` | 162 |
| `INFO` | 78 |
| `canary_env` | 48 |
| `CONFIG` | 41 |


_Generated from first-party honeypot capture. CC BY 4.0._
