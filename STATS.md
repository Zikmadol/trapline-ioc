# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1529 attackers** · **339,340 hostile actions** · covering 21 day(s) through 2026-10-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 107 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 110 |
| Stage-2 hosts named in payloads | 26 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 646 |
| `ssh-bruteforce` | 359 |
| `redis-exploit` | 292 |
| `mcp-abuse` | 97 |
| `llamacpp-abuse` | 28 |
| `litellm-key-replay` | 24 |
| `ollama-abuse` | 17 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1035 |
| `redis` | 300 |
| `mcp` | 138 |
| `llamacpp` | 88 |
| `vllm` | 56 |
| `jupyter` | 47 |
| `litellm` | 47 |
| `hfhub` | 42 |
| `docker` | 34 |
| `ollama` | 27 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 611 |
| `345gs5662d34` | 518 |
| `admin` | 318 |
| `ubuntu` | 143 |
| `administrator` | 84 |
| `test` | 71 |
| `user` | 64 |
| `admin1` | 63 |
| `ftpuser` | 60 |
| `AdminGPON` | 55 |
| `a` | 55 |
| `aaa` | 54 |
| `admin2` | 54 |
| `adminuser` | 53 |
| `admin123` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 519 |
| `345gs5662d34` | 517 |
| `123456` | 344 |
| `123` | 209 |
| `1234` | 182 |
| `12345678` | 110 |
| `admin` | 107 |
| `12345` | 85 |
| `password` | 82 |
| `1` | 80 |
| `000000` | 77 |
| `123456789` | 64 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `!Q2w3e4r` | 58 |

### Top commands run

| command | times |
|---|---|
| `uname` | 682 |
| `echo` | 603 |
| `lscpu` | 590 |
| `crontab` | 589 |
| `cd` | 579 |
| `cat` | 579 |
| `ls` | 534 |
| `top` | 534 |
| `df` | 533 |
| `free` | 533 |
| `whoami` | 532 |
| `w` | 531 |
| `INFO` | 192 |
| `PING` | 126 |
| `canary_env` | 124 |


_Generated from first-party honeypot capture. CC BY 4.0._
