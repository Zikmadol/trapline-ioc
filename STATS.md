# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2986 attackers** · **598,246 hostile actions** · covering 40 day(s) through 2026-10-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 184 |
| Used a planted canary credential | 31 |
| Seen on more than one sensor | 208 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2653 |
| `ssh-exploit` | 1179 |
| `ssh-bruteforce` | 665 |
| `redis-exploit` | 552 |
| `mcp-abuse` | 232 |
| `llamacpp-abuse` | 76 |
| `ollama-abuse` | 56 |
| `litellm-key-replay` | 48 |
| `docker-abuse` | 35 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1918 |
| `redis` | 566 |
| `mcp` | 333 |
| `llamacpp` | 207 |
| `jupyter` | 131 |
| `vllm` | 125 |
| `litellm` | 117 |
| `hfhub` | 97 |
| `ollama` | 95 |
| `docker` | 86 |
| `ray` | 20 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1096 |
| `345gs5662d34` | 944 |
| `admin` | 654 |
| `ubuntu` | 307 |
| `user` | 158 |
| `ftpuser` | 155 |
| `test` | 131 |
| `git` | 107 |
| `deploy` | 105 |
| `postgres` | 104 |
| `guest` | 95 |
| `administrator` | 92 |
| `oracle` | 72 |
| `ftp` | 69 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 942 |
| `3245gs5662d34` | 935 |
| `123456` | 766 |
| `123` | 506 |
| `1234` | 363 |
| `12345678` | 279 |
| `admin` | 235 |
| `12345` | 228 |
| `1` | 222 |
| `P@ssw0rd` | 162 |
| `password` | 157 |
| `admin123` | 145 |
| `000000` | 117 |
| `123456789` | 115 |
| `!QAZ2wsx` | 101 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1291 |
| `cat` | 1109 |
| `cd` | 1109 |
| `echo` | 1095 |
| `crontab` | 1073 |
| `lscpu` | 1071 |
| `ls` | 970 |
| `free` | 969 |
| `df` | 967 |
| `top` | 967 |
| `whoami` | 966 |
| `w` | 965 |
| `INFO` | 372 |
| `canary_env` | 285 |
| `PING` | 256 |


_Generated from first-party honeypot capture. CC BY 4.0._
