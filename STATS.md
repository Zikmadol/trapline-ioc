# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**384 attackers** · **86,692 hostile actions** · covering 8 day(s) through 2026-09-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 28 |
| Used a planted canary credential | 1 |
| Seen on more than one sensor | 5 |
| Stage-2 hosts named in payloads | 15 |

### By category

| category | IPs |
|---|---|
| `ssh-bruteforce` | 129 |
| `ssh-exploit` | 123 |
| `redis-exploit` | 65 |
| `mcp-abuse` | 34 |
| `llamacpp-abuse` | 9 |
| `llamacpp-key-replay` | 2 |
| `vllm-abuse` | 2 |
| `jupyter-abuse` | 1 |
| `jupyter-key-replay` | 1 |
| `ollama-abuse` | 1 |
| `vllm-bruteforce` | 1 |
| `docker-abuse` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 253 |
| `redis` | 67 |
| `mcp` | 37 |
| `llamacpp` | 20 |
| `vllm` | 11 |
| `jupyter` | 8 |
| `ray` | 5 |
| `docker` | 4 |
| `hfhub` | 4 |
| `litellm` | 4 |
| `ollama` | 2 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 134 |
| `345gs5662d34` | 91 |
| `admin` | 77 |
| `administrator` | 28 |
| `admin1` | 24 |
| `admin2` | 22 |
| `admin123` | 21 |
| `adminuser` | 21 |
| `ai` | 21 |
| `AdminGPON` | 20 |
| `a` | 20 |
| `aaa` | 20 |
| `Asalem` | 19 |
| `Caps` | 19 |
| `abigail` | 19 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 91 |
| `3245gs5662d34` | 90 |
| `123456` | 72 |
| `1234` | 39 |
| `123` | 37 |
| `12345678` | 33 |
| `admin` | 32 |
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
| `uname` | 131 |
| `echo` | 104 |
| `lscpu` | 101 |
| `crontab` | 100 |
| `cat` | 94 |
| `df` | 93 |
| `whoami` | 93 |
| `ls` | 93 |
| `cd` | 93 |
| `top` | 93 |
| `w` | 92 |
| `free` | 91 |
| `INFO` | 48 |
| `canary_env` | 42 |
| `CONFIG` | 26 |


_Generated from first-party honeypot capture. CC BY 4.0._
