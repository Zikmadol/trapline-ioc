# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2253 attackers** · **452,891 hostile actions** · covering 30 day(s) through 2026-10-12

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 161 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 926 |
| `ssh-bruteforce` | 522 |
| `redis-exploit` | 424 |
| `mcp-abuse` | 173 |
| `llamacpp-abuse` | 47 |
| `litellm-key-replay` | 32 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 23 |
| `canary-aws-key` | 19 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1494 |
| `redis` | 437 |
| `mcp` | 239 |
| `llamacpp` | 135 |
| `vllm` | 87 |
| `jupyter` | 85 |
| `litellm` | 76 |
| `hfhub` | 69 |
| `docker` | 56 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 853 |
| `345gs5662d34` | 735 |
| `admin` | 491 |
| `ubuntu` | 238 |
| `user` | 123 |
| `ftpuser` | 110 |
| `test` | 108 |
| `administrator` | 77 |
| `git` | 74 |
| `postgres` | 72 |
| `guest` | 68 |
| `deploy` | 67 |
| `admin1` | 59 |
| `oracle` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 734 |
| `3245gs5662d34` | 731 |
| `123456` | 559 |
| `123` | 358 |
| `1234` | 280 |
| `12345678` | 184 |
| `admin` | 180 |
| `12345` | 175 |
| `1` | 155 |
| `password` | 119 |
| `P@ssw0rd` | 111 |
| `admin123` | 107 |
| `000000` | 98 |
| `123456789` | 91 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1010 |
| `echo` | 860 |
| `cd` | 859 |
| `cat` | 858 |
| `crontab` | 842 |
| `lscpu` | 842 |
| `ls` | 755 |
| `free` | 754 |
| `top` | 754 |
| `df` | 753 |
| `whoami` | 752 |
| `w` | 751 |
| `INFO` | 284 |
| `canary_env` | 207 |
| `PING` | 192 |


_Generated from first-party honeypot capture. CC BY 4.0._
