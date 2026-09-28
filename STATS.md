# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1064 attackers** · **229,825 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 60 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 62 |
| Stage-2 hosts named in payloads | 19 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 412 |
| `ssh-bruteforce` | 258 |
| `redis-exploit` | 223 |
| `mcp-abuse` | 75 |
| `llamacpp-abuse` | 21 |
| `litellm-key-replay` | 15 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 689 |
| `redis` | 231 |
| `mcp` | 106 |
| `llamacpp` | 66 |
| `vllm` | 41 |
| `jupyter` | 37 |
| `hfhub` | 34 |
| `litellm` | 30 |
| `docker` | 22 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 383 |
| `345gs5662d34` | 326 |
| `admin` | 210 |
| `administrator` | 63 |
| `ubuntu` | 59 |
| `admin1` | 50 |
| `AdminGPON` | 43 |
| `aaa` | 43 |
| `a` | 42 |
| `admin2` | 42 |
| `adminuser` | 42 |
| `ai` | 41 |
| `admin123` | 40 |
| `Asalem` | 39 |
| `Caps` | 39 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 326 |
| `345gs5662d34` | 326 |
| `123456` | 186 |
| `123` | 115 |
| `1234` | 94 |
| `admin` | 69 |
| `12345678` | 55 |
| `000000` | 52 |
| `12345` | 47 |
| `!QAZ2wsx` | 46 |
| `0` | 44 |
| `1` | 43 |
| `123456789` | 43 |
| `0000` | 43 |
| `!Q2w3e4r` | 42 |

### Top commands run

| command | times |
|---|---|
| `uname` | 421 |
| `echo` | 376 |
| `lscpu` | 368 |
| `crontab` | 365 |
| `cd` | 363 |
| `cat` | 363 |
| `top` | 338 |
| `ls` | 337 |
| `df` | 337 |
| `free` | 337 |
| `whoami` | 336 |
| `w` | 335 |
| `INFO` | 152 |
| `canary_env` | 94 |
| `PING` | 88 |


_Generated from first-party honeypot capture. CC BY 4.0._
