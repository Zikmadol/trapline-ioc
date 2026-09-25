# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**816 attackers** · **173,314 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 46 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 312 |
| `ssh-bruteforce` | 219 |
| `redis-exploit` | 170 |
| `mcp-abuse` | 55 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 9 |
| `ollama-abuse` | 7 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 3 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 547 |
| `redis` | 175 |
| `mcp` | 75 |
| `llamacpp` | 49 |
| `vllm` | 27 |
| `jupyter` | 23 |
| `hfhub` | 18 |
| `docker` | 16 |
| `litellm` | 9 |
| `ollama` | 9 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 288 |
| `345gs5662d34` | 246 |
| `admin` | 167 |
| `administrator` | 49 |
| `admin1` | 41 |
| `ubuntu` | 40 |
| `admin2` | 34 |
| `AdminGPON` | 33 |
| `a` | 33 |
| `aaa` | 33 |
| `adminuser` | 33 |
| `ai` | 33 |
| `Asalem` | 31 |
| `admin123` | 31 |
| `aishani` | 31 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 246 |
| `3245gs5662d34` | 245 |
| `123456` | 144 |
| `123` | 84 |
| `1234` | 72 |
| `admin` | 56 |
| `000000` | 44 |
| `12345678` | 43 |
| `12345` | 37 |
| `123456789` | 37 |
| `!QAZ2wsx` | 37 |
| `0000` | 36 |
| `password` | 34 |
| `0` | 34 |
| `!Q2w3e4r` | 33 |

### Top commands run

| command | times |
|---|---|
| `uname` | 320 |
| `echo` | 286 |
| `lscpu` | 280 |
| `crontab` | 278 |
| `cat` | 271 |
| `cd` | 270 |
| `ls` | 257 |
| `top` | 257 |
| `df` | 256 |
| `free` | 256 |
| `whoami` | 255 |
| `w` | 254 |
| `INFO` | 116 |
| `canary_env` | 67 |
| `PING` | 59 |


_Generated from first-party honeypot capture. CC BY 4.0._
