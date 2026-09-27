# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1017 attackers** · **223,986 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 57 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 58 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 394 |
| `ssh-bruteforce` | 251 |
| `redis-exploit` | 216 |
| `mcp-abuse` | 71 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `litellm-key-replay` | 6 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 664 |
| `redis` | 224 |
| `mcp` | 100 |
| `llamacpp` | 66 |
| `vllm` | 39 |
| `jupyter` | 36 |
| `hfhub` | 33 |
| `docker` | 22 |
| `litellm` | 21 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 370 |
| `345gs5662d34` | 313 |
| `admin` | 202 |
| `administrator` | 62 |
| `ubuntu` | 54 |
| `admin1` | 49 |
| `aaa` | 42 |
| `AdminGPON` | 41 |
| `a` | 41 |
| `admin2` | 41 |
| `adminuser` | 41 |
| `ai` | 40 |
| `admin123` | 39 |
| `Asalem` | 38 |
| `Caps` | 38 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 313 |
| `345gs5662d34` | 313 |
| `123456` | 180 |
| `123` | 110 |
| `1234` | 90 |
| `admin` | 64 |
| `12345678` | 53 |
| `000000` | 51 |
| `12345` | 45 |
| `!QAZ2wsx` | 45 |
| `123456789` | 43 |
| `0` | 43 |
| `0000` | 42 |
| `password` | 41 |
| `1` | 41 |

### Top commands run

| command | times |
|---|---|
| `uname` | 403 |
| `echo` | 361 |
| `lscpu` | 353 |
| `crontab` | 350 |
| `cd` | 348 |
| `cat` | 348 |
| `top` | 324 |
| `ls` | 323 |
| `df` | 323 |
| `free` | 323 |
| `whoami` | 322 |
| `w` | 321 |
| `INFO` | 146 |
| `canary_env` | 90 |
| `PING` | 84 |


_Generated from first-party honeypot capture. CC BY 4.0._
