# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1485 attackers** · **334,039 hostile actions** · covering 21 day(s) through 2026-10-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 103 |
| Used a planted canary credential | 4 |
| Seen on more than one sensor | 103 |
| Stage-2 hosts named in payloads | 24 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 629 |
| `ssh-bruteforce` | 351 |
| `redis-exploit` | 285 |
| `mcp-abuse` | 95 |
| `llamacpp-abuse` | 26 |
| `litellm-key-replay` | 23 |
| `docker-abuse` | 16 |
| `ollama-abuse` | 12 |
| `canary-aws-key` | 10 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 3 |
| `vllm-key-replay` | 3 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1007 |
| `redis` | 293 |
| `mcp` | 134 |
| `llamacpp` | 83 |
| `vllm` | 52 |
| `jupyter` | 45 |
| `litellm` | 44 |
| `hfhub` | 41 |
| `docker` | 33 |
| `ollama` | 21 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 595 |
| `345gs5662d34` | 506 |
| `admin` | 307 |
| `ubuntu` | 135 |
| `administrator` | 84 |
| `test` | 68 |
| `admin1` | 63 |
| `user` | 62 |
| `AdminGPON` | 55 |
| `ftpuser` | 55 |
| `a` | 54 |
| `admin2` | 54 |
| `adminuser` | 54 |
| `ai` | 53 |
| `aaa` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 507 |
| `345gs5662d34` | 505 |
| `123456` | 332 |
| `123` | 200 |
| `1234` | 175 |
| `12345678` | 104 |
| `admin` | 100 |
| `password` | 80 |
| `12345` | 79 |
| `1` | 78 |
| `000000` | 76 |
| `!QAZ2wsx` | 63 |
| `0` | 62 |
| `123456789` | 61 |
| `0000` | 57 |

### Top commands run

| command | times |
|---|---|
| `uname` | 663 |
| `echo` | 590 |
| `lscpu` | 577 |
| `crontab` | 576 |
| `cd` | 565 |
| `cat` | 565 |
| `ls` | 522 |
| `top` | 522 |
| `df` | 521 |
| `free` | 521 |
| `whoami` | 520 |
| `w` | 519 |
| `INFO` | 187 |
| `PING` | 121 |
| `canary_env` | 120 |


_Generated from first-party honeypot capture. CC BY 4.0._
