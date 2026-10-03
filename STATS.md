# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1517 attackers** · **338,277 hostile actions** · covering 21 day(s) through 2026-10-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 106 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 110 |
| Stage-2 hosts named in payloads | 25 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 642 |
| `ssh-bruteforce` | 357 |
| `redis-exploit` | 292 |
| `mcp-abuse` | 97 |
| `llamacpp-abuse` | 28 |
| `litellm-key-replay` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `ollama-abuse` | 12 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1029 |
| `redis` | 300 |
| `mcp` | 138 |
| `llamacpp` | 87 |
| `vllm` | 54 |
| `jupyter` | 47 |
| `litellm` | 47 |
| `hfhub` | 42 |
| `docker` | 34 |
| `ollama` | 22 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 606 |
| `345gs5662d34` | 515 |
| `admin` | 313 |
| `ubuntu` | 140 |
| `administrator` | 84 |
| `test` | 69 |
| `user` | 63 |
| `admin1` | 63 |
| `ftpuser` | 59 |
| `AdminGPON` | 55 |
| `a` | 55 |
| `admin2` | 54 |
| `adminuser` | 54 |
| `aaa` | 53 |
| `ai` | 53 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 516 |
| `345gs5662d34` | 514 |
| `123456` | 341 |
| `123` | 204 |
| `1234` | 179 |
| `12345678` | 109 |
| `admin` | 105 |
| `12345` | 84 |
| `password` | 81 |
| `1` | 79 |
| `000000` | 76 |
| `123456789` | 63 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 678 |
| `echo` | 600 |
| `lscpu` | 587 |
| `crontab` | 586 |
| `cd` | 576 |
| `cat` | 576 |
| `ls` | 531 |
| `top` | 531 |
| `df` | 530 |
| `free` | 530 |
| `whoami` | 529 |
| `w` | 528 |
| `INFO` | 192 |
| `PING` | 126 |
| `canary_env` | 124 |


_Generated from first-party honeypot capture. CC BY 4.0._
