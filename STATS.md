# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1888 attackers** · **387,558 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 131 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 131 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 774 |
| `ssh-bruteforce` | 455 |
| `redis-exploit` | 355 |
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
| `ssh` | 1265 |
| `redis` | 366 |
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
| `root` | 729 |
| `345gs5662d34` | 621 |
| `admin` | 404 |
| `ubuntu` | 185 |
| `user` | 96 |
| `test` | 92 |
| `ftpuser` | 82 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `git` | 51 |
| `deploy` | 51 |
| `Asalem` | 50 |
| `postgres` | 49 |
| `admin2` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 621 |
| `345gs5662d34` | 620 |
| `123456` | 448 |
| `123` | 271 |
| `1234` | 226 |
| `admin` | 146 |
| `12345678` | 146 |
| `12345` | 125 |
| `1` | 123 |
| `password` | 103 |
| `000000` | 87 |
| `P@ssw0rd` | 82 |
| `admin123` | 81 |
| `123456789` | 78 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 844 |
| `echo` | 724 |
| `cd` | 712 |
| `lscpu` | 710 |
| `cat` | 710 |
| `crontab` | 709 |
| `ls` | 639 |
| `top` | 638 |
| `df` | 637 |
| `free` | 637 |
| `whoami` | 636 |
| `w` | 635 |
| `INFO` | 238 |
| `canary_env` | 157 |
| `PING` | 157 |


_Generated from first-party honeypot capture. CC BY 4.0._
