# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4258 attackers** · **872,389 hostile actions** · covering 54 day(s) through 2026-11-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 218 |
| Used a planted canary credential | 130 |
| Seen on more than one sensor | 320 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6491 |
| `ssh-exploit` | 1374 |
| `ssh-bruteforce` | 1154 |
| `redis-exploit` | 751 |
| `mcp-abuse` | 278 |
| `litellm-key-replay` | 133 |
| `llamacpp-abuse` | 101 |
| `ollama-abuse` | 100 |
| `docker-abuse` | 59 |
| `jupyter-abuse` | 39 |
| `vllm-abuse` | 18 |
| `llamacpp-key-replay` | 17 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2630 |
| `redis` | 775 |
| `mcp` | 446 |
| `llamacpp` | 327 |
| `litellm` | 248 |
| `vllm` | 201 |
| `jupyter` | 199 |
| `ollama` | 172 |
| `hfhub` | 159 |
| `docker` | 154 |
| `php` | 92 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1620 |
| `345gs5662d34` | 1098 |
| `admin` | 788 |
| `ubuntu` | 401 |
| `user` | 194 |
| `ftpuser` | 193 |
| `test` | 150 |
| `guest` | 134 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `ftp` | 105 |
| `administrator` | 102 |
| `oracle` | 90 |
| `AdminGPON` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 914 |
| `123` | 592 |
| `1234` | 423 |
| `12345678` | 346 |
| `admin` | 311 |
| `12345` | 268 |
| `1` | 267 |
| `P@ssw0rd` | 201 |
| `admin123` | 196 |
| `password` | 159 |
| `123456789` | 133 |
| `000000` | 129 |
| `!QAZ2wsx` | 113 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1492 |
| `cd` | 1291 |
| `cat` | 1289 |
| `echo` | 1266 |
| `crontab` | 1240 |
| `lscpu` | 1237 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 516 |
| `canary_env` | 372 |
| `PING` | 371 |


_Generated from first-party honeypot capture. CC BY 4.0._
