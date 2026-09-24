# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**753 attackers** · **158,763 hostile actions** · covering 12 day(s) through 2026-09-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 42 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 17 |
| Stage-2 hosts named in payloads | 17 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 280 |
| `ssh-bruteforce` | 211 |
| `redis-exploit` | 154 |
| `mcp-abuse` | 51 |
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
| `ssh` | 503 |
| `redis` | 159 |
| `mcp` | 69 |
| `llamacpp` | 42 |
| `vllm` | 24 |
| `jupyter` | 20 |
| `hfhub` | 17 |
| `docker` | 13 |
| `litellm` | 8 |
| `ollama` | 8 |
| `ray` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 263 |
| `345gs5662d34` | 219 |
| `admin` | 158 |
| `administrator` | 42 |
| `ubuntu` | 39 |
| `admin1` | 38 |
| `admin2` | 31 |
| `AdminGPON` | 30 |
| `aaa` | 30 |
| `adminuser` | 30 |
| `ai` | 30 |
| `a` | 29 |
| `admin123` | 29 |
| `Asalem` | 28 |
| `actian` | 28 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 219 |
| `3245gs5662d34` | 218 |
| `123456` | 135 |
| `123` | 78 |
| `1234` | 69 |
| `admin` | 53 |
| `12345678` | 42 |
| `000000` | 41 |
| `12345` | 35 |
| `!QAZ2wsx` | 34 |
| `0000` | 33 |
| `password` | 31 |
| `123456789` | 31 |
| `0` | 31 |
| `!Q2w3e4r` | 30 |

### Top commands run

| command | times |
|---|---|
| `uname` | 288 |
| `echo` | 254 |
| `lscpu` | 249 |
| `crontab` | 247 |
| `cat` | 243 |
| `cd` | 242 |
| `ls` | 229 |
| `top` | 229 |
| `df` | 228 |
| `free` | 228 |
| `whoami` | 227 |
| `w` | 226 |
| `INFO` | 109 |
| `canary_env` | 63 |
| `PING` | 53 |


_Generated from first-party honeypot capture. CC BY 4.0._
