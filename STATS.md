# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**789 attackers** · **165,730 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 44 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 296 |
| `ssh-bruteforce` | 215 |
| `redis-exploit` | 167 |
| `mcp-abuse` | 53 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 8 |
| `ollama-abuse` | 7 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 527 |
| `redis` | 172 |
| `mcp` | 72 |
| `llamacpp` | 47 |
| `vllm` | 26 |
| `jupyter` | 22 |
| `hfhub` | 18 |
| `docker` | 15 |
| `litellm` | 9 |
| `ollama` | 9 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 273 |
| `345gs5662d34` | 233 |
| `admin` | 161 |
| `administrator` | 48 |
| `admin1` | 40 |
| `ubuntu` | 40 |
| `admin2` | 33 |
| `AdminGPON` | 32 |
| `aaa` | 32 |
| `adminuser` | 32 |
| `ai` | 32 |
| `a` | 31 |
| `Asalem` | 30 |
| `admin123` | 30 |
| `actian` | 29 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 233 |
| `3245gs5662d34` | 232 |
| `123456` | 139 |
| `123` | 82 |
| `1234` | 70 |
| `admin` | 54 |
| `000000` | 43 |
| `12345678` | 43 |
| `123456789` | 37 |
| `12345` | 36 |
| `!QAZ2wsx` | 36 |
| `0000` | 35 |
| `password` | 33 |
| `0` | 33 |
| `1` | 32 |

### Top commands run

| command | times |
|---|---|
| `uname` | 304 |
| `echo` | 271 |
| `lscpu` | 265 |
| `crontab` | 263 |
| `cat` | 257 |
| `cd` | 256 |
| `ls` | 243 |
| `top` | 243 |
| `df` | 242 |
| `free` | 242 |
| `whoami` | 241 |
| `w` | 240 |
| `INFO` | 115 |
| `canary_env` | 65 |
| `PING` | 59 |


_Generated from first-party honeypot capture. CC BY 4.0._
