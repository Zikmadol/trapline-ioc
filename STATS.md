# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**857 attackers** · **179,387 hostile actions** · covering 13 day(s) through 2026-09-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 47 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 22 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 331 |
| `ssh-bruteforce` | 225 |
| `redis-exploit` | 180 |
| `mcp-abuse` | 59 |
| `llamacpp-abuse` | 17 |
| `docker-abuse` | 9 |
| `ollama-abuse` | 8 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 572 |
| `redis` | 186 |
| `mcp` | 80 |
| `llamacpp` | 54 |
| `vllm` | 28 |
| `jupyter` | 26 |
| `hfhub` | 20 |
| `docker` | 18 |
| `ollama` | 10 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 304 |
| `345gs5662d34` | 258 |
| `admin` | 174 |
| `administrator` | 50 |
| `ubuntu` | 43 |
| `admin1` | 42 |
| `aaa` | 35 |
| `admin2` | 35 |
| `AdminGPON` | 34 |
| `a` | 34 |
| `adminuser` | 34 |
| `ai` | 34 |
| `Asalem` | 32 |
| `admin123` | 32 |
| `Caps` | 31 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 258 |
| `3245gs5662d34` | 256 |
| `123456` | 149 |
| `123` | 91 |
| `1234` | 75 |
| `admin` | 60 |
| `000000` | 44 |
| `12345678` | 44 |
| `12345` | 39 |
| `123456789` | 38 |
| `!QAZ2wsx` | 38 |
| `0000` | 37 |
| `password` | 36 |
| `0` | 35 |
| `1` | 34 |

### Top commands run

| command | times |
|---|---|
| `uname` | 337 |
| `echo` | 300 |
| `lscpu` | 293 |
| `crontab` | 290 |
| `cat` | 288 |
| `cd` | 287 |
| `top` | 269 |
| `ls` | 268 |
| `df` | 268 |
| `free` | 267 |
| `whoami` | 267 |
| `w` | 266 |
| `INFO` | 123 |
| `canary_env` | 72 |
| `PING` | 66 |


_Generated from first-party honeypot capture. CC BY 4.0._
