# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6288 attackers** · **1,371,598 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 342 |
| Used a planted canary credential | 269 |
| Seen on more than one sensor | 515 |
| Stage-2 hosts named in payloads | 73 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13585 |
| `ssh-bruteforce` | 1955 |
| `ssh-exploit` | 1471 |
| `redis-exploit` | 1144 |
| `mcp-abuse` | 350 |
| `llamacpp-abuse` | 224 |
| `docker-abuse` | 222 |
| `litellm-key-replay` | 206 |
| `ollama-abuse` | 169 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 33 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3590 |
| `redis` | 1176 |
| `mcp` | 696 |
| `llamacpp` | 620 |
| `vllm` | 489 |
| `litellm` | 432 |
| `docker` | 374 |
| `jupyter` | 327 |
| `ollama` | 301 |
| `hfhub` | 265 |
| `php` | 199 |
| `ray` | 69 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1947 |
| `345gs5662d34` | 1107 |
| `admin` | 957 |
| `ubuntu` | 442 |
| `guest` | 241 |
| `ftpuser` | 234 |
| `user` | 222 |
| `test` | 175 |
| `ftp` | 149 |
| `config` | 134 |
| `deploy` | 129 |
| `git` | 126 |
| `bin` | 118 |
| `administrator` | 117 |
| `george` | 116 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1096 |
| `123456` | 1042 |
| `123` | 637 |
| `1234` | 532 |
| `admin` | 419 |
| `12345678` | 410 |
| `12345` | 356 |
| `1` | 303 |
| `admin123` | 264 |
| `P@ssw0rd` | 256 |
| `password` | 172 |
| `1111` | 153 |
| `123456789` | 151 |
| `000000` | 147 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1610 |
| `cat` | 1381 |
| `cd` | 1376 |
| `echo` | 1349 |
| `crontab` | 1316 |
| `lscpu` | 1309 |
| `ls` | 1198 |
| `free` | 1192 |
| `whoami` | 1192 |
| `df` | 1189 |
| `top` | 1188 |
| `w` | 1188 |
| `INFO` | 809 |
| `PING` | 633 |
| `canary_env` | 593 |


_Generated from first-party honeypot capture. CC BY 4.0._
