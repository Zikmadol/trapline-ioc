# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1021 attackers** · **224,088 hostile actions** · covering 15 day(s) through 2026-09-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 57 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 59 |
| Stage-2 hosts named in payloads | 18 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 396 |
| `ssh-bruteforce` | 251 |
| `redis-exploit` | 216 |
| `mcp-abuse` | 73 |
| `llamacpp-abuse` | 21 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `litellm-key-replay` | 6 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `llamacpp-key-replay` | 2 |
| `jupyter-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 666 |
| `redis` | 224 |
| `mcp` | 102 |
| `llamacpp` | 66 |
| `vllm` | 39 |
| `jupyter` | 36 |
| `hfhub` | 33 |
| `docker` | 22 |
| `litellm` | 21 |
| `ollama` | 15 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 371 |
| `345gs5662d34` | 315 |
| `admin` | 203 |
| `administrator` | 62 |
| `ubuntu` | 54 |
| `admin1` | 49 |
| `aaa` | 42 |
| `AdminGPON` | 41 |
| `a` | 41 |
| `admin2` | 41 |
| `adminuser` | 41 |
| `ai` | 40 |
| `admin123` | 39 |
| `Asalem` | 38 |
| `Caps` | 38 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 315 |
| `345gs5662d34` | 315 |
| `123456` | 180 |
| `123` | 112 |
| `1234` | 90 |
| `admin` | 64 |
| `12345678` | 53 |
| `000000` | 51 |
| `12345` | 45 |
| `!QAZ2wsx` | 45 |
| `123456789` | 43 |
| `0` | 43 |
| `0000` | 42 |
| `password` | 41 |
| `1` | 41 |

### Top commands run

| command | times |
|---|---|
| `uname` | 405 |
| `echo` | 363 |
| `lscpu` | 355 |
| `crontab` | 352 |
| `cd` | 350 |
| `cat` | 350 |
| `top` | 326 |
| `ls` | 325 |
| `df` | 325 |
| `free` | 325 |
| `whoami` | 324 |
| `w` | 323 |
| `INFO` | 146 |
| `canary_env` | 92 |
| `PING` | 84 |


_Generated from first-party honeypot capture. CC BY 4.0._
