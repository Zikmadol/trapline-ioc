# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4467 attackers** · **1,000,139 hostile actions** · covering 57 day(s) through 2026-11-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 222 |
| Used a planted canary credential | 150 |
| Seen on more than one sensor | 344 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7645 |
| `ssh-exploit` | 1388 |
| `ssh-bruteforce` | 1179 |
| `redis-exploit` | 832 |
| `mcp-abuse` | 287 |
| `litellm-key-replay` | 155 |
| `ollama-abuse` | 117 |
| `llamacpp-abuse` | 106 |
| `docker-abuse` | 63 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `php-abuse` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2680 |
| `redis` | 858 |
| `mcp` | 476 |
| `llamacpp` | 356 |
| `litellm` | 281 |
| `jupyter` | 233 |
| `vllm` | 231 |
| `ollama` | 199 |
| `hfhub` | 175 |
| `docker` | 165 |
| `php` | 105 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1641 |
| `345gs5662d34` | 1098 |
| `admin` | 806 |
| `ubuntu` | 408 |
| `ftpuser` | 198 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 140 |
| `git` | 117 |
| `deploy` | 113 |
| `ftp` | 111 |
| `postgres` | 108 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 85 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 927 |
| `123` | 597 |
| `1234` | 429 |
| `12345678` | 357 |
| `admin` | 327 |
| `12345` | 273 |
| `1` | 268 |
| `admin123` | 207 |
| `P@ssw0rd` | 207 |
| `password` | 160 |
| `000000` | 133 |
| `123456789` | 132 |
| `!QAZ2wsx` | 119 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1503 |
| `cd` | 1299 |
| `cat` | 1297 |
| `echo` | 1268 |
| `crontab` | 1241 |
| `lscpu` | 1238 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 580 |
| `PING` | 429 |
| `canary_env` | 387 |


_Generated from first-party honeypot capture. CC BY 4.0._
