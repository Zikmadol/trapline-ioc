# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2127 attackers** · **430,356 hostile actions** · covering 28 day(s) through 2026-10-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 145 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 150 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 877 |
| `ssh-bruteforce` | 494 |
| `redis-exploit` | 398 |
| `mcp-abuse` | 158 |
| `llamacpp-abuse` | 45 |
| `litellm-key-replay` | 31 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 22 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1414 |
| `redis` | 409 |
| `mcp` | 217 |
| `llamacpp` | 126 |
| `jupyter` | 78 |
| `vllm` | 78 |
| `litellm` | 68 |
| `hfhub` | 64 |
| `docker` | 52 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 813 |
| `345gs5662d34` | 702 |
| `admin` | 465 |
| `ubuntu` | 218 |
| `user` | 106 |
| `test` | 104 |
| `ftpuser` | 99 |
| `administrator` | 76 |
| `git` | 69 |
| `guest` | 64 |
| `deploy` | 62 |
| `postgres` | 61 |
| `AdminGPON` | 57 |
| `admin1` | 56 |
| `debian` | 54 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 702 |
| `345gs5662d34` | 701 |
| `123456` | 523 |
| `123` | 326 |
| `1234` | 266 |
| `12345678` | 176 |
| `admin` | 169 |
| `12345` | 165 |
| `1` | 150 |
| `password` | 113 |
| `P@ssw0rd` | 104 |
| `000000` | 96 |
| `admin123` | 96 |
| `123456789` | 89 |
| `!QAZ2wsx` | 82 |

### Top commands run

| command | times |
|---|---|
| `uname` | 955 |
| `echo` | 820 |
| `cd` | 811 |
| `cat` | 809 |
| `crontab` | 803 |
| `lscpu` | 803 |
| `ls` | 722 |
| `top` | 721 |
| `df` | 720 |
| `free` | 720 |
| `whoami` | 719 |
| `w` | 718 |
| `INFO` | 264 |
| `canary_env` | 191 |
| `PING` | 182 |


_Generated from first-party honeypot capture. CC BY 4.0._
