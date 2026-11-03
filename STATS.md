# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4106 attackers** · **836,627 hostile actions** · covering 52 day(s) through 2026-11-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 215 |
| Used a planted canary credential | 86 |
| Seen on more than one sensor | 302 |
| Stage-2 hosts named in payloads | 56 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5968 |
| `ssh-exploit` | 1363 |
| `ssh-bruteforce` | 1137 |
| `redis-exploit` | 718 |
| `mcp-abuse` | 272 |
| `litellm-key-replay` | 123 |
| `llamacpp-abuse` | 92 |
| `ollama-abuse` | 89 |
| `docker-abuse` | 57 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 16 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2595 |
| `redis` | 739 |
| `mcp` | 426 |
| `llamacpp` | 296 |
| `litellm` | 226 |
| `vllm` | 187 |
| `jupyter` | 182 |
| `ollama` | 149 |
| `docker` | 143 |
| `hfhub` | 141 |
| `php` | 83 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1609 |
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
| `123456` | 902 |
| `123` | 587 |
| `1234` | 417 |
| `12345678` | 337 |
| `admin` | 303 |
| `1` | 265 |
| `12345` | 263 |
| `P@ssw0rd` | 196 |
| `admin123` | 188 |
| `password` | 157 |
| `123456789` | 132 |
| `000000` | 129 |
| `!QAZ2wsx` | 113 |

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
| `INFO` | 489 |
| `canary_env` | 355 |
| `PING` | 348 |


_Generated from first-party honeypot capture. CC BY 4.0._
