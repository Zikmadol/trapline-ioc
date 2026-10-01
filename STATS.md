# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1330 attackers** · **292,122 hostile actions** · covering 19 day(s) through 2026-10-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 87 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 92 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 562 |
| `ssh-bruteforce` | 313 |
| `redis-exploit` | 260 |
| `mcp-abuse` | 84 |
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
| `ssh` | 897 |
| `redis` | 268 |
| `mcp` | 121 |
| `llamacpp` | 76 |
| `vllm` | 48 |
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
| `admin` | 271 |
| `ubuntu` | 114 |
| `administrator` | 83 |
| `admin1` | 65 |
| `user` | 56 |
| `admin2` | 55 |
| `a` | 54 |
| `ai` | 54 |
| `test` | 53 |
| `AdminGPON` | 53 |
| `adminuser` | 53 |
| `aaa` | 52 |
| `admin123` | 50 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 453 |
| `345gs5662d34` | 451 |
| `123456` | 277 |
| `123` | 159 |
| `1234` | 139 |
| `12345678` | 83 |
| `admin` | 82 |
| `password` | 71 |
| `1` | 68 |
| `000000` | 68 |
| `12345` | 68 |
| `!QAZ2wsx` | 58 |
| `0` | 56 |
| `123456789` | 54 |
| `!Q2w3e4r` | 54 |

### Top commands run

| command | times |
|---|---|
| `uname` | 585 |
| `echo` | 522 |
| `lscpu` | 510 |
| `crontab` | 509 |
| `cd` | 502 |
| `cat` | 501 |
| `top` | 466 |
| `ls` | 465 |
| `df` | 465 |
| `free` | 465 |
| `whoami` | 464 |
| `w` | 463 |
| `INFO` | 173 |
| `canary_env` | 105 |
| `PING` | 105 |


_Generated from first-party honeypot capture. CC BY 4.0._
