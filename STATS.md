# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1229 attackers** · **275,759 hostile actions** · covering 17 day(s) through 2026-09-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 76 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 78 |
| Stage-2 hosts named in payloads | 22 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 507 |
| `ssh-bruteforce` | 297 |
| `redis-exploit` | 245 |
| `mcp-abuse` | 78 |
| `llamacpp-abuse` | 22 |
| `litellm-key-replay` | 17 |
| `docker-abuse` | 12 |
| `ollama-abuse` | 10 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `llamacpp-key-replay` | 2 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 824 |
| `redis` | 253 |
| `mcp` | 112 |
| `llamacpp` | 72 |
| `vllm` | 43 |
| `jupyter` | 38 |
| `hfhub` | 35 |
| `litellm` | 33 |
| `docker` | 25 |
| `ollama` | 17 |
| `ray` | 8 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 477 |
| `345gs5662d34` | 404 |
| `admin` | 249 |
| `ubuntu` | 93 |
| `administrator` | 77 |
| `admin1` | 63 |
| `a` | 53 |
| `ai` | 53 |
| `aaa` | 51 |
| `admin2` | 51 |
| `AdminGPON` | 50 |
| `adminuser` | 50 |
| `admin123` | 48 |
| `Asalem` | 47 |
| `Caps` | 47 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 404 |
| `345gs5662d34` | 404 |
| `123456` | 229 |
| `123` | 133 |
| `1234` | 115 |
| `admin` | 77 |
| `12345678` | 71 |
| `000000` | 63 |
| `password` | 62 |
| `12345` | 60 |
| `1` | 58 |
| `!QAZ2wsx` | 54 |
| `0` | 52 |
| `0000` | 51 |
| `!Q2w3e4r` | 50 |

### Top commands run

| command | times |
|---|---|
| `uname` | 523 |
| `echo` | 466 |
| `lscpu` | 456 |
| `crontab` | 453 |
| `cd` | 451 |
| `cat` | 451 |
| `top` | 418 |
| `ls` | 417 |
| `df` | 417 |
| `free` | 417 |
| `whoami` | 416 |
| `w` | 415 |
| `INFO` | 164 |
| `PING` | 98 |
| `canary_env` | 97 |


_Generated from first-party honeypot capture. CC BY 4.0._
