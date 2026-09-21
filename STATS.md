# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**411 attackers** · **90,141 hostile actions** · covering 9 day(s) through 2026-09-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 28 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 4 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 137 |
| `ssh-exploit` | 137 |
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
| `ssh` | 275 |
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
| `root` | 150 |
| `345gs5662d34` | 105 |
| `admin` | 84 |
| `administrator` | 29 |
| `admin1` | 24 |
| `admin2` | 23 |
| `AdminGPON` | 22 |
| `adminuser` | 22 |
| `a` | 21 |
| `aaa` | 21 |
| `admin123` | 21 |
| `ai` | 21 |
| `Asalem` | 20 |
| `Caps` | 19 |
| `abigail` | 19 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 105 |
| `3245gs5662d34` | 104 |
| `123456` | 79 |
| `123` | 43 |
| `1234` | 40 |
| `admin` | 35 |
| `12345678` | 34 |
| `000000` | 32 |
| `12345` | 30 |
| `123456789` | 29 |
| `0000` | 24 |
| `!QAZ2wsx` | 24 |
| `0` | 23 |
| `123123` | 22 |
| `1234567` | 21 |

### Top commands run

| command | times |
|---|---|
| `uname` | 146 |
| `echo` | 121 |
| `lscpu` | 117 |
| `crontab` | 116 |
| `ls` | 108 |
| `cd` | 108 |
| `cat` | 108 |
| `top` | 108 |
| `df` | 107 |
| `w` | 107 |
| `whoami` | 107 |
| `free` | 106 |
| `INFO` | 51 |
| `canary_env` | 41 |
| `CONFIG` | 28 |


_Generated from first-party honeypot capture. CC BY 4.0._
