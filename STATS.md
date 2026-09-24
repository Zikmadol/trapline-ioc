# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**765 attackers** · **159,204 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 42 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 21 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 281 |
| `ssh-bruteforce` | 212 |
| `redis-exploit` | 163 |
| `mcp-abuse` | 52 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 8 |
| `ollama-abuse` | 6 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 509 |
| `redis` | 168 |
| `mcp` | 71 |
| `llamacpp` | 44 |
| `vllm` | 25 |
| `jupyter` | 21 |
| `hfhub` | 18 |
| `docker` | 14 |
| `litellm` | 9 |
| `ollama` | 8 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 264 |
| `345gs5662d34` | 220 |
| `admin` | 159 |
| `administrator` | 42 |
| `ubuntu` | 39 |
| `admin1` | 38 |
| `admin2` | 31 |
| `AdminGPON` | 30 |
| `a` | 30 |
| `aaa` | 30 |
| `adminuser` | 30 |
| `ai` | 30 |
| `admin123` | 29 |
| `Asalem` | 28 |
| `actian` | 28 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 220 |
| `3245gs5662d34` | 219 |
| `123456` | 135 |
| `123` | 78 |
| `1234` | 70 |
| `admin` | 54 |
| `12345678` | 42 |
| `000000` | 41 |
| `12345` | 35 |
| `!QAZ2wsx` | 34 |
| `0000` | 33 |
| `password` | 31 |
| `123456789` | 31 |
| `0` | 31 |
| `1` | 30 |

### Top commands run

| command | times |
|---|---|
| `uname` | 289 |
| `echo` | 255 |
| `lscpu` | 250 |
| `crontab` | 248 |
| `cat` | 244 |
| `cd` | 243 |
| `ls` | 230 |
| `top` | 230 |
| `df` | 229 |
| `free` | 229 |
| `whoami` | 228 |
| `w` | 227 |
| `INFO` | 113 |
| `canary_env` | 64 |
| `PING` | 58 |


_Generated from first-party honeypot capture. CC BY 4.0._
