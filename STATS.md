# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2285 attackers** · **456,005 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 14 |
| Seen on more than one sensor | 163 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 934 |
| `ssh-bruteforce` | 528 |
| `redis-exploit` | 427 |
| `canary-aws-key` | 197 |
| `mcp-abuse` | 179 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 34 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1509 |
| `redis` | 440 |
| `mcp` | 247 |
| `llamacpp` | 140 |
| `jupyter` | 87 |
| `vllm` | 87 |
| `litellm` | 78 |
| `hfhub` | 69 |
| `docker` | 59 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 862 |
| `345gs5662d34` | 745 |
| `admin` | 495 |
| `ubuntu` | 242 |
| `user` | 123 |
| `ftpuser` | 112 |
| `test` | 108 |
| `administrator` | 79 |
| `git` | 77 |
| `postgres` | 75 |
| `guest` | 69 |
| `deploy` | 68 |
| `admin1` | 59 |
| `AdminGPON` | 57 |
| `oracle` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 744 |
| `3245gs5662d34` | 741 |
| `123456` | 568 |
| `123` | 362 |
| `1234` | 282 |
| `12345678` | 186 |
| `admin` | 182 |
| `12345` | 178 |
| `1` | 160 |
| `password` | 120 |
| `P@ssw0rd` | 115 |
| `admin123` | 108 |
| `000000` | 98 |
| `123456789` | 95 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1020 |
| `echo` | 871 |
| `cd` | 869 |
| `cat` | 868 |
| `crontab` | 852 |
| `lscpu` | 852 |
| `ls` | 765 |
| `free` | 764 |
| `top` | 764 |
| `df` | 763 |
| `whoami` | 762 |
| `w` | 761 |
| `INFO` | 286 |
| `canary_env` | 215 |
| `PING` | 192 |


_Generated from first-party honeypot capture. CC BY 4.0._
