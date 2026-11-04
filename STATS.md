# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4148 attackers** · **845,405 hostile actions** · covering 53 day(s) through 2026-11-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 216 |
| Used a planted canary credential | 100 |
| Seen on more than one sensor | 305 |
| Stage-2 hosts named in payloads | 56 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6124 |
| `ssh-exploit` | 1365 |
| `ssh-bruteforce` | 1140 |
| `redis-exploit` | 727 |
| `mcp-abuse` | 274 |
| `litellm-key-replay` | 122 |
| `llamacpp-abuse` | 95 |
| `ollama-abuse` | 95 |
| `docker-abuse` | 57 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 17 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2601 |
| `redis` | 751 |
| `mcp` | 433 |
| `llamacpp` | 310 |
| `litellm` | 230 |
| `vllm` | 193 |
| `jupyter` | 187 |
| `ollama` | 158 |
| `hfhub` | 148 |
| `docker` | 145 |
| `php` | 86 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1609 |
| `345gs5662d34` | 1098 |
| `admin` | 777 |
| `ubuntu` | 394 |
| `user` | 191 |
| `ftpuser` | 188 |
| `test` | 149 |
| `guest` | 129 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `administrator` | 102 |
| `ftp` | 101 |
| `oracle` | 89 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 904 |
| `123` | 588 |
| `1234` | 418 |
| `12345678` | 339 |
| `admin` | 305 |
| `1` | 265 |
| `12345` | 264 |
| `P@ssw0rd` | 197 |
| `admin123` | 190 |
| `password` | 158 |
| `123456789` | 132 |
| `000000` | 129 |
| `!QAZ2wsx` | 113 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1483 |
| `cd` | 1284 |
| `cat` | 1282 |
| `echo` | 1265 |
| `crontab` | 1239 |
| `lscpu` | 1236 |
| `ls` | 1128 |
| `whoami` | 1127 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 499 |
| `canary_env` | 362 |
| `PING` | 356 |


_Generated from first-party honeypot capture. CC BY 4.0._
