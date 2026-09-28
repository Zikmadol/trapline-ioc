# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1072 attackers** · **232,008 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 61 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 63 |
| Stage-2 hosts named in payloads | 20 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 417 |
| `ssh-bruteforce` | 259 |
| `redis-exploit` | 224 |
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
| `ssh` | 695 |
| `redis` | 232 |
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
| `root` | 386 |
| `345gs5662d34` | 330 |
| `admin` | 212 |
| `administrator` | 64 |
| `ubuntu` | 59 |
| `admin1` | 51 |
| `AdminGPON` | 43 |
| `a` | 43 |
| `aaa` | 43 |
| `admin2` | 43 |
| `adminuser` | 42 |
| `ai` | 42 |
| `Asalem` | 40 |
| `Caps` | 40 |
| `admin123` | 40 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 330 |
| `345gs5662d34` | 330 |
| `123456` | 188 |
| `123` | 118 |
| `1234` | 95 |
| `admin` | 69 |
| `12345678` | 55 |
| `000000` | 53 |
| `12345` | 47 |
| `!QAZ2wsx` | 47 |
| `0` | 45 |
| `1` | 44 |
| `123456789` | 43 |
| `0000` | 43 |
| `!Q2w3e4r` | 43 |

### Top commands run

| command | times |
|---|---|
| `uname` | 426 |
| `echo` | 381 |
| `lscpu` | 373 |
| `crontab` | 370 |
| `cd` | 367 |
| `cat` | 367 |
| `top` | 342 |
| `ls` | 341 |
| `df` | 341 |
| `free` | 341 |
| `whoami` | 340 |
| `w` | 339 |
| `INFO` | 152 |
| `canary_env` | 94 |
| `PING` | 88 |


_Generated from first-party honeypot capture. CC BY 4.0._
