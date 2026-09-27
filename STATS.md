# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1040 attackers** · **229,422 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 59 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 60 |
| Stage-2 hosts named in payloads | 19 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 403 |
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
| `ssh` | 678 |
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
| `root` | 378 |
| `345gs5662d34` | 319 |
| `admin` | 206 |
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
| `3245gs5662d34` | 319 |
| `345gs5662d34` | 319 |
| `123456` | 184 |
| `123` | 114 |
| `1234` | 91 |
| `admin` | 66 |
| `12345678` | 54 |
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
| `uname` | 413 |
| `echo` | 369 |
| `lscpu` | 361 |
| `crontab` | 358 |
| `cd` | 356 |
| `cat` | 356 |
| `top` | 331 |
| `ls` | 330 |
| `df` | 330 |
| `free` | 330 |
| `whoami` | 329 |
| `w` | 328 |
| `INFO` | 151 |
| `canary_env` | 92 |
| `PING` | 88 |


_Generated from first-party honeypot capture. CC BY 4.0._
