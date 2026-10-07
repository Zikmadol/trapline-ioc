# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1858 attackers** · **384,088 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 130 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 126 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 763 |
| `ssh-bruteforce` | 452 |
| `redis-exploit` | 348 |
| `mcp-abuse` | 121 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 11 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1249 |
| `redis` | 359 |
| `mcp` | 170 |
| `llamacpp` | 106 |
| `jupyter` | 62 |
| `vllm` | 62 |
| `litellm` | 58 |
| `hfhub` | 50 |
| `docker` | 41 |
| `ollama` | 37 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 724 |
| `345gs5662d34` | 613 |
| `admin` | 394 |
| `ubuntu` | 180 |
| `user` | 93 |
| `test` | 92 |
| `ftpuser` | 80 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 54 |
| `deploy` | 51 |
| `Asalem` | 51 |
| `postgres` | 50 |
| `git` | 49 |
| `Caps` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 613 |
| `345gs5662d34` | 612 |
| `123456` | 442 |
| `123` | 264 |
| `1234` | 222 |
| `admin` | 144 |
| `12345678` | 144 |
| `12345` | 124 |
| `1` | 120 |
| `password` | 102 |
| `000000` | 87 |
| `123456789` | 78 |
| `admin123` | 78 |
| `P@ssw0rd` | 76 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 833 |
| `echo` | 716 |
| `lscpu` | 702 |
| `cd` | 702 |
| `crontab` | 701 |
| `cat` | 700 |
| `ls` | 631 |
| `top` | 630 |
| `df` | 629 |
| `free` | 629 |
| `whoami` | 628 |
| `w` | 627 |
| `INFO` | 232 |
| `PING` | 154 |
| `canary_env` | 151 |


_Generated from first-party honeypot capture. CC BY 4.0._
