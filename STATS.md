# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1327 attackers** · **289,408 hostile actions** · covering 18 day(s) through 2026-09-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 85 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 92 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 560 |
| `ssh-bruteforce` | 313 |
| `redis-exploit` | 260 |
| `mcp-abuse` | 83 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 21 |
| `docker-abuse` | 13 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 895 |
| `redis` | 268 |
| `mcp` | 120 |
| `llamacpp` | 76 |
| `vllm` | 46 |
| `jupyter` | 42 |
| `litellm` | 41 |
| `hfhub` | 36 |
| `docker` | 28 |
| `ollama` | 19 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 532 |
| `345gs5662d34` | 451 |
| `admin` | 268 |
| `ubuntu` | 115 |
| `administrator` | 82 |
| `admin1` | 64 |
| `user` | 56 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `test` | 52 |
| `AdminGPON` | 52 |
| `aaa` | 52 |
| `adminuser` | 52 |
| `admin123` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 453 |
| `345gs5662d34` | 451 |
| `123456` | 275 |
| `123` | 157 |
| `1234` | 138 |
| `admin` | 82 |
| `12345678` | 82 |
| `password` | 71 |
| `000000` | 68 |
| `12345` | 67 |
| `1` | 66 |
| `!QAZ2wsx` | 56 |
| `0` | 55 |
| `123456789` | 53 |
| `0000` | 53 |

### Top commands run

| command | times |
|---|---|
| `uname` | 583 |
| `echo` | 521 |
| `lscpu` | 509 |
| `crontab` | 507 |
| `cd` | 502 |
| `cat` | 501 |
| `top` | 466 |
| `ls` | 465 |
| `df` | 465 |
| `free` | 465 |
| `whoami` | 464 |
| `w` | 463 |
| `INFO` | 173 |
| `PING` | 105 |
| `canary_env` | 104 |


_Generated from first-party honeypot capture. CC BY 4.0._
