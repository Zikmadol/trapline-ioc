# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**499 attackers** · **111,973 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 32 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 7 |
| Stage-2 hosts named in payloads | 16 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 172 |
| `ssh-bruteforce` | 160 |
| `redis-exploit` | 89 |
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
| `ssh` | 337 |
| `redis` | 91 |
| `mcp` | 43 |
| `llamacpp` | 24 |
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
| `root` | 185 |
| `345gs5662d34` | 138 |
| `admin` | 98 |
| `administrator` | 32 |
| `admin1` | 30 |
| `admin2` | 27 |
| `admin123` | 26 |
| `AdminGPON` | 25 |
| `a` | 25 |
| `aaa` | 25 |
| `adminuser` | 25 |
| `ai` | 25 |
| `Asalem` | 23 |
| `Caps` | 23 |
| `abigail` | 23 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 138 |
| `3245gs5662d34` | 137 |
| `123456` | 98 |
| `123` | 51 |
| `1234` | 48 |
| `admin` | 40 |
| `000000` | 36 |
| `12345678` | 36 |
| `12345` | 32 |
| `123456789` | 29 |
| `!QAZ2wsx` | 29 |
| `0000` | 27 |
| `0` | 27 |
| `!qaz@WSX` | 25 |
| `00000000` | 25 |

### Top commands run

| command | times |
|---|---|
| `uname` | 184 |
| `echo` | 159 |
| `lscpu` | 156 |
| `crontab` | 154 |
| `ls` | 142 |
| `cd` | 142 |
| `cat` | 142 |
| `top` | 142 |
| `df` | 141 |
| `w` | 141 |
| `whoami` | 141 |
| `free` | 140 |
| `INFO` | 66 |
| `canary_env` | 46 |
| `CONFIG` | 37 |


_Generated from first-party honeypot capture. CC BY 4.0._
