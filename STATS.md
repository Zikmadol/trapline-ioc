# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1350 attackers** · **296,278 hostile actions** · covering 19 day(s) through 2026-10-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 87 |
| Used a planted canary credential | 0 |
| Seen on more than one sensor | 93 |
| Stage-2 hosts named in payloads | 23 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 570 |
| `ssh-bruteforce` | 323 |
| `redis-exploit` | 260 |
| `mcp-abuse` | 85 |
| `llamacpp-abuse` | 23 |
| `litellm-key-replay` | 21 |
| `docker-abuse` | 14 |
| `ollama-abuse` | 11 |
| `vllm-abuse` | 5 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |
| `litellm-abuse` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 916 |
| `redis` | 268 |
| `mcp` | 122 |
| `llamacpp` | 76 |
| `vllm` | 48 |
| `jupyter` | 42 |
| `litellm` | 41 |
| `hfhub` | 36 |
| `docker` | 29 |
| `ollama` | 19 |
| `ray` | 9 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 544 |
| `345gs5662d34` | 459 |
| `admin` | 275 |
| `ubuntu` | 117 |
| `administrator` | 87 |
| `admin1` | 65 |
| `user` | 61 |
| `admin2` | 56 |
| `a` | 55 |
| `ai` | 55 |
| `test` | 54 |
| `AdminGPON` | 53 |
| `aaa` | 53 |
| `adminuser` | 53 |
| `admin123` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 462 |
| `345gs5662d34` | 459 |
| `123456` | 283 |
| `123` | 163 |
| `1234` | 149 |
| `admin` | 84 |
| `12345678` | 83 |
| `password` | 72 |
| `000000` | 69 |
| `12345` | 69 |
| `1` | 67 |
| `!QAZ2wsx` | 58 |
| `123456789` | 56 |
| `0` | 56 |
| `0000` | 54 |

### Top commands run

| command | times |
|---|---|
| `uname` | 593 |
| `echo` | 530 |
| `lscpu` | 518 |
| `crontab` | 517 |
| `cd` | 510 |
| `cat` | 509 |
| `top` | 474 |
| `ls` | 473 |
| `df` | 473 |
| `free` | 473 |
| `whoami` | 472 |
| `w` | 471 |
| `INFO` | 173 |
| `canary_env` | 106 |
| `PING` | 105 |


_Generated from first-party honeypot capture. CC BY 4.0._
