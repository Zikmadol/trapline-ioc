# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1882 attackers** · **386,901 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 131 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 131 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 772 |
| `ssh-bruteforce` | 453 |
| `redis-exploit` | 353 |
| `mcp-abuse` | 126 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1261 |
| `redis` | 364 |
| `mcp` | 177 |
| `llamacpp` | 109 |
| `vllm` | 65 |
| `jupyter` | 64 |
| `litellm` | 58 |
| `hfhub` | 51 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 731 |
| `345gs5662d34` | 621 |
| `admin` | 400 |
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
| `3245gs5662d34` | 621 |
| `345gs5662d34` | 620 |
| `123456` | 446 |
| `123` | 269 |
| `1234` | 225 |
| `admin` | 145 |
| `12345678` | 145 |
| `12345` | 124 |
| `1` | 122 |
| `password` | 103 |
| `000000` | 87 |
| `P@ssw0rd` | 81 |
| `admin123` | 80 |
| `123456789` | 78 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 842 |
| `echo` | 724 |
| `lscpu` | 710 |
| `cd` | 710 |
| `crontab` | 709 |
| `cat` | 708 |
| `ls` | 639 |
| `top` | 638 |
| `df` | 637 |
| `free` | 637 |
| `whoami` | 636 |
| `w` | 635 |
| `INFO` | 236 |
| `canary_env` | 157 |
| `PING` | 156 |


_Generated from first-party honeypot capture. CC BY 4.0._
