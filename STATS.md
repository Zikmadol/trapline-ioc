# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1052 attackers** · **229,803 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 59 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 62 |
| Stage-2 hosts named in payloads | 19 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 411 |
| `ssh-bruteforce` | 257 |
| `redis-exploit` | 222 |
| `mcp-abuse` | 74 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `litellm-key-replay` | 7 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 687 |
| `redis` | 230 |
| `mcp` | 105 |
| `llamacpp` | 66 |
| `vllm` | 41 |
| `jupyter` | 37 |
| `hfhub` | 34 |
| `litellm` | 22 |
| `docker` | 22 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 382 |
| `345gs5662d34` | 326 |
| `admin` | 209 |
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
| `admin` | 67 |
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
| `uname` | 420 |
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
| `INFO` | 151 |
| `canary_env` | 93 |
| `PING` | 88 |


_Generated from first-party honeypot capture. CC BY 4.0._
