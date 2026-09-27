# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1037 attackers** · **229,310 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 58 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 59 |
| Stage-2 hosts named in payloads | 19 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 402 |
| `ssh-bruteforce` | 255 |
| `redis-exploit` | 220 |
| `mcp-abuse` | 73 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `litellm-key-replay` | 6 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 676 |
| `redis` | 228 |
| `mcp` | 103 |
| `llamacpp` | 66 |
| `vllm` | 40 |
| `jupyter` | 36 |
| `hfhub` | 33 |
| `docker` | 22 |
| `litellm` | 21 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 376 |
| `345gs5662d34` | 318 |
| `admin` | 206 |
| `administrator` | 63 |
| `ubuntu` | 55 |
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
| `3245gs5662d34` | 318 |
| `345gs5662d34` | 318 |
| `123456` | 183 |
| `123` | 113 |
| `1234` | 91 |
| `admin` | 66 |
| `12345678` | 54 |
| `000000` | 52 |
| `!QAZ2wsx` | 46 |
| `12345` | 45 |
| `0` | 44 |
| `123456789` | 43 |
| `0000` | 43 |
| `1` | 42 |
| `!Q2w3e4r` | 42 |

### Top commands run

| command | times |
|---|---|
| `uname` | 411 |
| `echo` | 368 |
| `lscpu` | 360 |
| `crontab` | 357 |
| `cd` | 355 |
| `cat` | 355 |
| `top` | 330 |
| `ls` | 329 |
| `df` | 329 |
| `free` | 329 |
| `whoami` | 328 |
| `w` | 327 |
| `INFO` | 150 |
| `canary_env` | 92 |
| `PING` | 87 |


_Generated from first-party honeypot capture. CC BY 4.0._
