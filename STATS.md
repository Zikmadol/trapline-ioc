# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**928 attackers** · **190,891 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 51 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 37 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 363 |
| `ssh-bruteforce` | 235 |
| `redis-exploit` | 196 |
| `mcp-abuse` | 64 |
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
| `ssh` | 614 |
| `redis` | 202 |
| `mcp` | 88 |
| `llamacpp` | 58 |
| `vllm` | 31 |
| `jupyter` | 27 |
| `hfhub` | 22 |
| `docker` | 18 |
| `ollama` | 12 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 336 |
| `345gs5662d34` | 287 |
| `admin` | 186 |
| `administrator` | 57 |
| `ubuntu` | 51 |
| `admin1` | 44 |
| `admin2` | 38 |
| `aaa` | 37 |
| `adminuser` | 37 |
| `ai` | 37 |
| `a` | 36 |
| `AdminGPON` | 35 |
| `actian` | 34 |
| `admin123` | 34 |
| `airflow` | 34 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 287 |
| `3245gs5662d34` | 286 |
| `123456` | 163 |
| `123` | 101 |
| `1234` | 82 |
| `admin` | 63 |
| `12345678` | 47 |
| `000000` | 46 |
| `12345` | 41 |
| `!QAZ2wsx` | 41 |
| `123456789` | 40 |
| `0000` | 40 |
| `password` | 39 |
| `1` | 39 |
| `0` | 38 |

### Top commands run

| command | times |
|---|---|
| `uname` | 371 |
| `echo` | 332 |
| `lscpu` | 324 |
| `crontab` | 321 |
| `cat` | 320 |
| `cd` | 319 |
| `top` | 297 |
| `ls` | 296 |
| `df` | 296 |
| `free` | 296 |
| `whoami` | 295 |
| `w` | 294 |
| `INFO` | 134 |
| `canary_env` | 80 |
| `PING` | 71 |


_Generated from first-party honeypot capture. CC BY 4.0._
