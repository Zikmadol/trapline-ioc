# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1909 attackers** · **391,155 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 134 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 132 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 784 |
| `ssh-bruteforce` | 457 |
| `redis-exploit` | 357 |
| `mcp-abuse` | 129 |
| `llamacpp-abuse` | 41 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 8 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1278 |
| `redis` | 368 |
| `mcp` | 181 |
| `llamacpp` | 112 |
| `vllm` | 66 |
| `jupyter` | 65 |
| `litellm` | 58 |
| `hfhub` | 51 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 737 |
| `345gs5662d34` | 628 |
| `admin` | 409 |
| `ubuntu` | 189 |
| `user` | 100 |
| `test` | 94 |
| `ftpuser` | 85 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `git` | 51 |
| `deploy` | 51 |
| `Asalem` | 50 |
| `guest` | 49 |
| `postgres` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 628 |
| `345gs5662d34` | 627 |
| `123456` | 454 |
| `123` | 274 |
| `1234` | 229 |
| `12345678` | 148 |
| `admin` | 147 |
| `12345` | 126 |
| `1` | 123 |
| `password` | 103 |
| `000000` | 88 |
| `123456789` | 82 |
| `P@ssw0rd` | 82 |
| `admin123` | 82 |
| `!QAZ2wsx` | 72 |

### Top commands run

| command | times |
|---|---|
| `uname` | 856 |
| `echo` | 733 |
| `cd` | 721 |
| `lscpu` | 719 |
| `cat` | 719 |
| `crontab` | 718 |
| `ls` | 646 |
| `top` | 645 |
| `df` | 644 |
| `free` | 644 |
| `whoami` | 643 |
| `w` | 642 |
| `INFO` | 239 |
| `canary_env` | 161 |
| `PING` | 158 |


_Generated from first-party honeypot capture. CC BY 4.0._
