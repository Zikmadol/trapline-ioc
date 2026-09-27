# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1032 attackers** · **229,187 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 58 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 59 |
| Stage-2 hosts named in payloads | 19 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 400 |
| `ssh-bruteforce` | 252 |
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
| `ssh` | 671 |
| `redis` | 228 |
| `mcp` | 102 |
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
| `root` | 373 |
| `345gs5662d34` | 316 |
| `admin` | 204 |
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
| `3245gs5662d34` | 316 |
| `345gs5662d34` | 316 |
| `123456` | 182 |
| `123` | 113 |
| `1234` | 91 |
| `admin` | 64 |
| `12345678` | 53 |
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
| `uname` | 409 |
| `echo` | 366 |
| `lscpu` | 358 |
| `crontab` | 355 |
| `cd` | 353 |
| `cat` | 353 |
| `top` | 328 |
| `ls` | 327 |
| `df` | 327 |
| `free` | 327 |
| `whoami` | 326 |
| `w` | 325 |
| `INFO` | 150 |
| `canary_env` | 92 |
| `PING` | 87 |


_Generated from first-party honeypot capture. CC BY 4.0._
