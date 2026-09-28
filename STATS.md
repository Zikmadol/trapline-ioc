# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1159 attackers** · **248,129 hostile actions** · covering 16 day(s) through 2026-09-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 69 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 71 |
| Stage-2 hosts named in payloads | 21 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 477 |
| `ssh-bruteforce` | 275 |
| `redis-exploit` | 230 |
| `mcp-abuse` | 76 |
| `llamacpp-abuse` | 22 |
| `litellm-key-replay` | 17 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 771 |
| `redis` | 238 |
| `mcp` | 107 |
| `llamacpp` | 68 |
| `vllm` | 42 |
| `jupyter` | 37 |
| `hfhub` | 34 |
| `litellm` | 33 |
| `docker` | 23 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 440 |
| `345gs5662d34` | 379 |
| `admin` | 227 |
| `ubuntu` | 72 |
| `administrator` | 71 |
| `admin1` | 55 |
| `admin2` | 47 |
| `ai` | 47 |
| `AdminGPON` | 46 |
| `a` | 46 |
| `aaa` | 46 |
| `adminuser` | 45 |
| `admin123` | 43 |
| `Asalem` | 42 |
| `Caps` | 42 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 379 |
| `345gs5662d34` | 379 |
| `123456` | 209 |
| `123` | 123 |
| `1234` | 103 |
| `admin` | 73 |
| `12345678` | 64 |
| `000000` | 56 |
| `password` | 55 |
| `12345` | 55 |
| `1` | 50 |
| `!QAZ2wsx` | 49 |
| `0` | 47 |
| `0000` | 46 |
| `123456789` | 45 |

### Top commands run

| command | times |
|---|---|
| `uname` | 487 |
| `echo` | 433 |
| `lscpu` | 425 |
| `crontab` | 422 |
| `cd` | 421 |
| `cat` | 421 |
| `top` | 392 |
| `ls` | 391 |
| `df` | 391 |
| `free` | 391 |
| `whoami` | 390 |
| `w` | 389 |
| `INFO` | 156 |
| `canary_env` | 95 |
| `PING` | 92 |


_Generated from first-party honeypot capture. CC BY 4.0._
