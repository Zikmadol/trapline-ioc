# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**775 attackers** · **159,635 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 42 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 21 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 286 |
| `ssh-bruteforce` | 214 |
| `redis-exploit` | 164 |
| `mcp-abuse` | 53 |
| `llamacpp-abuse` | 15 |
| `docker-abuse` | 8 |
| `ollama-abuse` | 7 |
| `vllm-abuse` | 4 |
| `jupyter-abuse` | 2 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 516 |
| `redis` | 169 |
| `mcp` | 72 |
| `llamacpp` | 45 |
| `vllm` | 26 |
| `jupyter` | 21 |
| `hfhub` | 18 |
| `docker` | 14 |
| `litellm` | 9 |
| `ollama` | 9 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 268 |
| `345gs5662d34` | 226 |
| `admin` | 159 |
| `administrator` | 44 |
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
| `345gs5662d34` | 226 |
| `3245gs5662d34` | 225 |
| `123456` | 137 |
| `123` | 80 |
| `1234` | 70 |
| `admin` | 54 |
| `12345678` | 43 |
| `000000` | 41 |
| `12345` | 35 |
| `123456789` | 34 |
| `!QAZ2wsx` | 34 |
| `0000` | 33 |
| `password` | 31 |
| `0` | 31 |
| `1` | 30 |

### Top commands run

| command | times |
|---|---|
| `uname` | 295 |
| `echo` | 262 |
| `lscpu` | 255 |
| `crontab` | 254 |
| `cat` | 250 |
| `cd` | 249 |
| `ls` | 236 |
| `top` | 236 |
| `free` | 235 |
| `df` | 234 |
| `w` | 233 |
| `whoami` | 233 |
| `INFO` | 113 |
| `canary_env` | 65 |
| `PING` | 58 |


_Generated from first-party honeypot capture. CC BY 4.0._
