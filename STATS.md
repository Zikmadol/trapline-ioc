# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**982 attackers** · **199,476 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 54 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 50 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 385 |
| `ssh-bruteforce` | 245 |
| `redis-exploit` | 208 |
| `mcp-abuse` | 70 |
| `llamacpp-abuse` | 21 |
| `ollama-abuse` | 10 |
| `docker-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 647 |
| `redis` | 215 |
| `mcp` | 95 |
| `llamacpp` | 62 |
| `vllm` | 36 |
| `jupyter` | 33 |
| `hfhub` | 30 |
| `docker` | 20 |
| `ollama` | 15 |
| `litellm` | 12 |
| `ray` | 7 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 358 |
| `345gs5662d34` | 306 |
| `admin` | 193 |
| `administrator` | 58 |
| `ubuntu` | 53 |
| `admin1` | 45 |
| `aaa` | 39 |
| `a` | 38 |
| `admin2` | 38 |
| `adminuser` | 38 |
| `ai` | 38 |
| `AdminGPON` | 37 |
| `Asalem` | 35 |
| `admin123` | 35 |
| `Caps` | 34 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 306 |
| `3245gs5662d34` | 305 |
| `123456` | 174 |
| `123` | 109 |
| `1234` | 88 |
| `admin` | 62 |
| `12345678` | 49 |
| `000000` | 48 |
| `12345` | 43 |
| `!QAZ2wsx` | 41 |
| `password` | 40 |
| `123456789` | 40 |
| `0000` | 40 |
| `1` | 39 |
| `0` | 39 |

### Top commands run

| command | times |
|---|---|
| `uname` | 394 |
| `echo` | 352 |
| `lscpu` | 344 |
| `crontab` | 341 |
| `cd` | 341 |
| `cat` | 341 |
| `top` | 317 |
| `ls` | 316 |
| `df` | 316 |
| `free` | 316 |
| `whoami` | 315 |
| `w` | 314 |
| `INFO` | 143 |
| `canary_env` | 87 |
| `PING` | 78 |


_Generated from first-party honeypot capture. CC BY 4.0._
