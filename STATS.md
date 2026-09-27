# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1047 attackers** · **229,687 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 59 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 60 |
| Stage-2 hosts named in payloads | 19 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 410 |
| `ssh-bruteforce` | 256 |
| `redis-exploit` | 221 |
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
| `ssh` | 685 |
| `redis` | 229 |
| `mcp` | 104 |
| `llamacpp` | 66 |
| `vllm` | 41 |
| `jupyter` | 37 |
| `hfhub` | 34 |
| `docker` | 22 |
| `litellm` | 21 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 381 |
| `345gs5662d34` | 325 |
| `admin` | 207 |
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
| `3245gs5662d34` | 325 |
| `345gs5662d34` | 325 |
| `123456` | 186 |
| `123` | 115 |
| `1234` | 94 |
| `admin` | 66 |
| `12345678` | 55 |
| `000000` | 52 |
| `12345` | 46 |
| `!QAZ2wsx` | 46 |
| `0` | 44 |
| `123456789` | 43 |
| `0000` | 43 |
| `1` | 42 |
| `!Q2w3e4r` | 42 |

### Top commands run

| command | times |
|---|---|
| `uname` | 419 |
| `echo` | 375 |
| `lscpu` | 367 |
| `crontab` | 364 |
| `cd` | 362 |
| `cat` | 362 |
| `top` | 337 |
| `ls` | 336 |
| `df` | 336 |
| `free` | 336 |
| `whoami` | 335 |
| `w` | 334 |
| `INFO` | 151 |
| `canary_env` | 92 |
| `PING` | 88 |


_Generated from first-party honeypot capture. CC BY 4.0._
