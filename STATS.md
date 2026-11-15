# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5122 attackers** · **1,160,707 hostile actions** · covering 64 day(s) through 2026-11-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 294 |
| Used a planted canary credential | 180 |
| Seen on more than one sensor | 438 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10249 |
| `ssh-bruteforce` | 1474 |
| `ssh-exploit` | 1402 |
| `redis-exploit` | 965 |
| `mcp-abuse` | 303 |
| `litellm-key-replay` | 173 |
| `docker-abuse` | 156 |
| `ollama-abuse` | 142 |
| `llamacpp-abuse` | 121 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3012 |
| `redis` | 996 |
| `mcp` | 520 |
| `llamacpp` | 408 |
| `litellm` | 322 |
| `vllm` | 315 |
| `docker` | 280 |
| `jupyter` | 265 |
| `ollama` | 250 |
| `hfhub` | 211 |
| `php` | 148 |
| `ray` | 46 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1721 |
| `345gs5662d34` | 1098 |
| `admin` | 877 |
| `ubuntu` | 415 |
| `ftpuser` | 212 |
| `user` | 205 |
| `guest` | 172 |
| `test` | 164 |
| `ftp` | 126 |
| `git` | 119 |
| `deploy` | 116 |
| `postgres` | 111 |
| `administrator` | 106 |
| `config` | 98 |
| `bin` | 93 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 958 |
| `123` | 602 |
| `1234` | 464 |
| `12345678` | 382 |
| `admin` | 355 |
| `12345` | 295 |
| `1` | 275 |
| `admin123` | 230 |
| `P@ssw0rd` | 223 |
| `password` | 171 |
| `123456789` | 143 |
| `000000` | 134 |
| `!QAZ2wsx` | 126 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1514 |
| `cat` | 1303 |
| `cd` | 1299 |
| `echo` | 1276 |
| `crontab` | 1245 |
| `lscpu` | 1242 |
| `ls` | 1131 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1124 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 686 |
| `PING` | 525 |
| `canary_env` | 419 |


_Generated from first-party honeypot capture. CC BY 4.0._
