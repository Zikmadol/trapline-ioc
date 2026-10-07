# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1879 attackers** · **386,392 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 131 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 131 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 771 |
| `ssh-bruteforce` | 453 |
| `redis-exploit` | 352 |
| `mcp-abuse` | 126 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 24 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1260 |
| `redis` | 363 |
| `mcp` | 177 |
| `llamacpp` | 108 |
| `jupyter` | 64 |
| `vllm` | 64 |
| `litellm` | 58 |
| `hfhub` | 51 |
| `docker` | 42 |
| `ollama` | 38 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 731 |
| `345gs5662d34` | 620 |
| `admin` | 399 |
| `ubuntu` | 184 |
| `user` | 96 |
| `test` | 92 |
| `ftpuser` | 81 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 54 |
| `git` | 51 |
| `deploy` | 51 |
| `postgres` | 50 |
| `Asalem` | 50 |
| `admin2` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 620 |
| `345gs5662d34` | 619 |
| `123456` | 445 |
| `123` | 269 |
| `1234` | 224 |
| `12345678` | 145 |
| `admin` | 144 |
| `12345` | 124 |
| `1` | 122 |
| `password` | 103 |
| `000000` | 87 |
| `P@ssw0rd` | 80 |
| `admin123` | 80 |
| `123456789` | 78 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 841 |
| `echo` | 723 |
| `lscpu` | 709 |
| `cd` | 709 |
| `crontab` | 708 |
| `cat` | 707 |
| `ls` | 638 |
| `top` | 637 |
| `df` | 636 |
| `free` | 636 |
| `whoami` | 635 |
| `w` | 634 |
| `INFO` | 235 |
| `canary_env` | 157 |
| `PING` | 156 |


_Generated from first-party honeypot capture. CC BY 4.0._
