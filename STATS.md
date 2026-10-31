# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3940 attackers** · **766,926 hostile actions** · covering 49 day(s) through 2026-10-31

| signal | count |
|---|---|
| GPU / AI-hardware probing | 208 |
| Used a planted canary credential | 55 |
| Seen on more than one sensor | 281 |
| Stage-2 hosts named in payloads | 52 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5162 |
| `ssh-exploit` | 1352 |
| `ssh-bruteforce` | 1110 |
| `redis-exploit` | 680 |
| `mcp-abuse` | 267 |
| `litellm-key-replay` | 101 |
| `llamacpp-abuse` | 89 |
| `ollama-abuse` | 78 |
| `docker-abuse` | 51 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 15 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2552 |
| `redis` | 699 |
| `mcp` | 409 |
| `llamacpp` | 279 |
| `litellm` | 196 |
| `vllm` | 175 |
| `jupyter` | 174 |
| `ollama` | 132 |
| `docker` | 132 |
| `hfhub` | 128 |
| `php` | 65 |
| `ray` | 32 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1582 |
| `345gs5662d34` | 1098 |
| `admin` | 745 |
| `ubuntu` | 372 |
| `user` | 186 |
| `ftpuser` | 184 |
| `test` | 140 |
| `guest` | 120 |
| `git` | 114 |
| `deploy` | 113 |
| `postgres` | 109 |
| `administrator` | 99 |
| `ftp` | 95 |
| `oracle` | 83 |
| `debian` | 77 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 885 |
| `123` | 581 |
| `1234` | 411 |
| `12345678` | 329 |
| `admin` | 291 |
| `1` | 260 |
| `12345` | 259 |
| `P@ssw0rd` | 192 |
| `admin123` | 182 |
| `password` | 158 |
| `123456789` | 128 |
| `000000` | 125 |
| `!QAZ2wsx` | 110 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1471 |
| `cd` | 1279 |
| `cat` | 1277 |
| `echo` | 1261 |
| `crontab` | 1236 |
| `lscpu` | 1233 |
| `ls` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `whoami` | 1122 |
| `INFO` | 461 |
| `canary_env` | 343 |
| `PING` | 329 |


_Generated from first-party honeypot capture. CC BY 4.0._
