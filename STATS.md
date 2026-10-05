# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1692 attackers** · **362,675 hostile actions** · covering 23 day(s) through 2026-10-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 116 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 119 |
| Stage-2 hosts named in payloads | 29 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 708 |
| `ssh-bruteforce` | 407 |
| `redis-exploit` | 315 |
| `mcp-abuse` | 108 |
| `llamacpp-abuse` | 32 |
| `litellm-key-replay` | 25 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `vllm-abuse` | 6 |
| `jupyter-abuse` | 4 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1146 |
| `redis` | 324 |
| `mcp` | 151 |
| `llamacpp` | 96 |
| `vllm` | 58 |
| `litellm` | 53 |
| `jupyter` | 52 |
| `hfhub` | 47 |
| `docker` | 36 |
| `ollama` | 35 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 676 |
| `345gs5662d34` | 565 |
| `admin` | 364 |
| `ubuntu` | 162 |
| `test` | 83 |
| `user` | 82 |
| `administrator` | 80 |
| `ftpuser` | 72 |
| `admin1` | 58 |
| `AdminGPON` | 56 |
| `a` | 54 |
| `Asalem` | 52 |
| `Caps` | 51 |
| `git` | 49 |
| `aaa` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 566 |
| `345gs5662d34` | 564 |
| `123456` | 403 |
| `123` | 237 |
| `1234` | 204 |
| `12345678` | 131 |
| `admin` | 128 |
| `1` | 108 |
| `12345` | 103 |
| `password` | 98 |
| `000000` | 83 |
| `P@ssw0rd` | 70 |
| `123456789` | 68 |
| `!QAZ2wsx` | 68 |
| `0` | 63 |

### Top commands run

| command | times |
|---|---|
| `uname` | 756 |
| `echo` | 658 |
| `lscpu` | 645 |
| `crontab` | 644 |
| `cd` | 641 |
| `cat` | 641 |
| `ls` | 584 |
| `top` | 583 |
| `df` | 582 |
| `free` | 582 |
| `whoami` | 581 |
| `w` | 580 |
| `INFO` | 209 |
| `canary_env` | 136 |
| `PING` | 135 |


_Generated from first-party honeypot capture. CC BY 4.0._
