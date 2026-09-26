# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**962 attackers** · **198,279 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 54 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 49 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 376 |
| `ssh-bruteforce` | 241 |
| `redis-exploit` | 205 |
| `mcp-abuse` | 68 |
| `llamacpp-abuse` | 21 |
| `ollama-abuse` | 9 |
| `docker-abuse` | 9 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 633 |
| `redis` | 212 |
| `mcp` | 92 |
| `llamacpp` | 61 |
| `vllm` | 35 |
| `jupyter` | 31 |
| `hfhub` | 26 |
| `docker` | 19 |
| `ollama` | 13 |
| `litellm` | 11 |
| `ray` | 7 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 348 |
| `345gs5662d34` | 298 |
| `admin` | 190 |
| `administrator` | 58 |
| `ubuntu` | 53 |
| `admin1` | 45 |
| `aaa` | 39 |
| `admin2` | 38 |
| `AdminGPON` | 37 |
| `a` | 37 |
| `adminuser` | 37 |
| `ai` | 37 |
| `Asalem` | 35 |
| `admin123` | 35 |
| `Caps` | 34 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 298 |
| `3245gs5662d34` | 297 |
| `123456` | 171 |
| `123` | 105 |
| `1234` | 87 |
| `admin` | 62 |
| `12345678` | 50 |
| `000000` | 47 |
| `12345` | 44 |
| `123456789` | 41 |
| `!QAZ2wsx` | 41 |
| `0000` | 40 |
| `password` | 39 |
| `0` | 39 |
| `1` | 38 |

### Top commands run

| command | times |
|---|---|
| `uname` | 385 |
| `echo` | 343 |
| `lscpu` | 335 |
| `crontab` | 332 |
| `cd` | 332 |
| `cat` | 332 |
| `top` | 308 |
| `ls` | 307 |
| `df` | 307 |
| `free` | 307 |
| `whoami` | 306 |
| `w` | 305 |
| `INFO` | 142 |
| `canary_env` | 84 |
| `PING` | 76 |


_Generated from first-party honeypot capture. CC BY 4.0._
