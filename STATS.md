# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2558 attackers** · **498,108 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 173 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 182 |
| Stage-2 hosts named in payloads | 36 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1025 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 595 |
| `redis-exploit` | 486 |
| `mcp-abuse` | 198 |
| `llamacpp-abuse` | 60 |
| `litellm-key-replay` | 40 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1674 |
| `redis` | 500 |
| `mcp` | 279 |
| `llamacpp` | 167 |
| `vllm` | 105 |
| `jupyter` | 99 |
| `litellm` | 95 |
| `hfhub` | 81 |
| `docker` | 70 |
| `ollama` | 48 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 967 |
| `345gs5662d34` | 820 |
| `admin` | 560 |
| `ubuntu` | 270 |
| `user` | 145 |
| `ftpuser` | 131 |
| `test` | 123 |
| `deploy` | 87 |
| `git` | 86 |
| `postgres` | 83 |
| `guest` | 80 |
| `administrator` | 80 |
| `oracle` | 63 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 818 |
| `3245gs5662d34` | 814 |
| `123456` | 658 |
| `123` | 420 |
| `1234` | 318 |
| `12345678` | 230 |
| `admin` | 209 |
| `12345` | 196 |
| `1` | 187 |
| `password` | 142 |
| `P@ssw0rd` | 139 |
| `admin123` | 127 |
| `000000` | 106 |
| `123456789` | 101 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1131 |
| `echo` | 962 |
| `cat` | 959 |
| `cd` | 959 |
| `crontab` | 942 |
| `lscpu` | 941 |
| `ls` | 844 |
| `free` | 843 |
| `df` | 841 |
| `top` | 841 |
| `whoami` | 840 |
| `w` | 839 |
| `INFO` | 323 |
| `canary_env` | 239 |
| `PING` | 218 |


_Generated from first-party honeypot capture. CC BY 4.0._
