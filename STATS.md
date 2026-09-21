# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**407 attackers** · **89,373 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 27 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 4 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 137 |
| `ssh-exploit` | 133 |
| `redis-exploit` | 69 |
| `mcp-abuse` | 34 |
| `llamacpp-abuse` | 9 |
| `llamacpp-key-replay` | 2 |
| `vllm-abuse` | 2 |
| `docker-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 271 |
| `redis` | 70 |
| `mcp` | 36 |
| `llamacpp` | 19 |
| `vllm` | 11 |
| `jupyter` | 7 |
| `ray` | 4 |
| `docker` | 4 |
| `hfhub` | 3 |
| `litellm` | 3 |
| `ollama` | 1 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 148 |
| `345gs5662d34` | 101 |
| `admin` | 79 |
| `administrator` | 28 |
| `admin1` | 24 |
| `admin2` | 23 |
| `AdminGPON` | 21 |
| `a` | 21 |
| `aaa` | 21 |
| `admin123` | 21 |
| `adminuser` | 21 |
| `ai` | 21 |
| `Asalem` | 19 |
| `Caps` | 19 |
| `abigail` | 19 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 101 |
| `3245gs5662d34` | 100 |
| `123456` | 77 |
| `123` | 41 |
| `1234` | 39 |
| `admin` | 34 |
| `12345678` | 33 |
| `000000` | 30 |
| `12345` | 30 |
| `123456789` | 28 |
| `!QAZ2wsx` | 24 |
| `0000` | 23 |
| `0` | 23 |
| `123123` | 21 |
| `1234567` | 21 |

### Top commands run

| command | times |
|---|---|
| `uname` | 141 |
| `echo` | 116 |
| `crontab` | 111 |
| `lscpu` | 111 |
| `ls` | 104 |
| `cd` | 104 |
| `cat` | 104 |
| `top` | 104 |
| `df` | 103 |
| `w` | 103 |
| `whoami` | 103 |
| `free` | 102 |
| `INFO` | 51 |
| `canary_env` | 41 |
| `CONFIG` | 28 |


_Generated from first-party honeypot capture. CC BY 4.0._
