# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**948 attackers** · **197,576 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 54 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 42 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 368 |
| `ssh-bruteforce` | 240 |
| `redis-exploit` | 205 |
| `mcp-abuse` | 65 |
| `llamacpp-abuse` | 19 |
| `ollama-abuse` | 10 |
| `docker-abuse` | 9 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 624 |
| `redis` | 211 |
| `mcp` | 89 |
| `llamacpp` | 59 |
| `vllm` | 34 |
| `jupyter` | 30 |
| `hfhub` | 25 |
| `docker` | 19 |
| `ollama` | 12 |
| `litellm` | 11 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 342 |
| `345gs5662d34` | 291 |
| `admin` | 189 |
| `administrator` | 58 |
| `ubuntu` | 52 |
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
| `345gs5662d34` | 291 |
| `3245gs5662d34` | 290 |
| `123456` | 168 |
| `123` | 103 |
| `1234` | 86 |
| `admin` | 62 |
| `12345678` | 49 |
| `000000` | 47 |
| `12345` | 43 |
| `!QAZ2wsx` | 41 |
| `123456789` | 40 |
| `0000` | 40 |
| `password` | 39 |
| `0` | 39 |
| `1` | 37 |

### Top commands run

| command | times |
|---|---|
| `uname` | 378 |
| `echo` | 336 |
| `lscpu` | 328 |
| `crontab` | 325 |
| `cat` | 325 |
| `cd` | 324 |
| `top` | 301 |
| `ls` | 300 |
| `df` | 300 |
| `free` | 300 |
| `whoami` | 299 |
| `w` | 298 |
| `INFO` | 141 |
| `canary_env` | 81 |
| `PING` | 75 |


_Generated from first-party honeypot capture. CC BY 4.0._
