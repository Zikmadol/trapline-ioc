# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**996 attackers** · **215,159 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 57 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 53 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 391 |
| `ssh-bruteforce` | 244 |
| `redis-exploit` | 212 |
| `mcp-abuse` | 70 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 11 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `litellm-key-replay` | 4 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 654 |
| `redis` | 219 |
| `mcp` | 96 |
| `llamacpp` | 63 |
| `vllm` | 37 |
| `jupyter` | 33 |
| `hfhub` | 31 |
| `docker` | 21 |
| `litellm` | 17 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 361 |
| `345gs5662d34` | 309 |
| `admin` | 196 |
| `administrator` | 61 |
| `ubuntu` | 53 |
| `admin1` | 47 |
| `aaa` | 41 |
| `admin2` | 40 |
| `adminuser` | 40 |
| `AdminGPON` | 39 |
| `a` | 39 |
| `ai` | 39 |
| `Asalem` | 37 |
| `admin123` | 37 |
| `admins` | 37 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 309 |
| `3245gs5662d34` | 308 |
| `123456` | 177 |
| `123` | 112 |
| `1234` | 91 |
| `admin` | 63 |
| `12345678` | 50 |
| `000000` | 49 |
| `12345` | 45 |
| `!QAZ2wsx` | 43 |
| `0000` | 42 |
| `0` | 42 |
| `123456789` | 41 |
| `1` | 40 |
| `!Q2w3e4r` | 40 |

### Top commands run

| command | times |
|---|---|
| `uname` | 399 |
| `echo` | 357 |
| `lscpu` | 349 |
| `crontab` | 346 |
| `cd` | 344 |
| `cat` | 344 |
| `top` | 320 |
| `ls` | 319 |
| `df` | 319 |
| `free` | 319 |
| `whoami` | 318 |
| `w` | 317 |
| `INFO` | 145 |
| `canary_env` | 87 |
| `PING` | 80 |


_Generated from first-party honeypot capture. CC BY 4.0._
