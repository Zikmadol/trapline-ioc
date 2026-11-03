# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4101 attackers** · **831,296 hostile actions** · covering 52 day(s) through 2026-11-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 215 |
| Used a planted canary credential | 86 |
| Seen on more than one sensor | 301 |
| Stage-2 hosts named in payloads | 56 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5950 |
| `ssh-exploit` | 1363 |
| `ssh-bruteforce` | 1136 |
| `redis-exploit` | 716 |
| `mcp-abuse` | 272 |
| `litellm-key-replay` | 122 |
| `llamacpp-abuse` | 92 |
| `ollama-abuse` | 89 |
| `docker-abuse` | 57 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 16 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2594 |
| `redis` | 736 |
| `mcp` | 426 |
| `llamacpp` | 295 |
| `litellm` | 225 |
| `vllm` | 187 |
| `jupyter` | 182 |
| `ollama` | 149 |
| `docker` | 143 |
| `hfhub` | 140 |
| `php` | 82 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1608 |
| `345gs5662d34` | 1098 |
| `admin` | 773 |
| `ubuntu` | 390 |
| `user` | 190 |
| `ftpuser` | 187 |
| `test` | 148 |
| `guest` | 127 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `administrator` | 102 |
| `ftp` | 100 |
| `oracle` | 88 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 903 |
| `123` | 588 |
| `1234` | 418 |
| `12345678` | 338 |
| `admin` | 303 |
| `1` | 266 |
| `12345` | 264 |
| `P@ssw0rd` | 196 |
| `admin123` | 189 |
| `password` | 157 |
| `123456789` | 132 |
| `000000` | 127 |
| `!QAZ2wsx` | 112 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1481 |
| `cd` | 1282 |
| `cat` | 1280 |
| `echo` | 1265 |
| `crontab` | 1239 |
| `lscpu` | 1236 |
| `ls` | 1128 |
| `free` | 1126 |
| `whoami` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 487 |
| `canary_env` | 355 |
| `PING` | 347 |


_Generated from first-party honeypot capture. CC BY 4.0._
