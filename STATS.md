# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**903 attackers** · **181,581 hostile actions** · covering 14 day(s) through 2026-09-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 48 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 32 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 351 |
| `ssh-bruteforce` | 231 |
| `redis-exploit` | 190 |
| `mcp-abuse` | 63 |
| `llamacpp-abuse` | 19 |
| `ollama-abuse` | 9 |
| `docker-abuse` | 9 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `jupyter-key-replay` | 2 |
| `llamacpp-key-replay` | 1 |
| `vllm-key-replay` | 1 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 598 |
| `redis` | 196 |
| `mcp` | 84 |
| `llamacpp` | 57 |
| `vllm` | 29 |
| `jupyter` | 27 |
| `hfhub` | 21 |
| `docker` | 18 |
| `ollama` | 11 |
| `litellm` | 9 |
| `ray` | 6 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 328 |
| `345gs5662d34` | 280 |
| `admin` | 179 |
| `administrator` | 55 |
| `ubuntu` | 47 |
| `admin1` | 42 |
| `aaa` | 36 |
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
| `345gs5662d34` | 280 |
| `3245gs5662d34` | 279 |
| `123456` | 160 |
| `123` | 99 |
| `1234` | 81 |
| `admin` | 62 |
| `12345678` | 46 |
| `000000` | 44 |
| `12345` | 40 |
| `123456789` | 40 |
| `!QAZ2wsx` | 38 |
| `password` | 37 |
| `1` | 37 |
| `0000` | 37 |
| `0` | 35 |

### Top commands run

| command | times |
|---|---|
| `uname` | 359 |
| `echo` | 322 |
| `lscpu` | 314 |
| `crontab` | 311 |
| `cat` | 311 |
| `cd` | 310 |
| `top` | 290 |
| `ls` | 289 |
| `df` | 289 |
| `free` | 289 |
| `whoami` | 288 |
| `w` | 287 |
| `INFO` | 132 |
| `canary_env` | 79 |
| `PING` | 68 |


_Generated from first-party honeypot capture. CC BY 4.0._
