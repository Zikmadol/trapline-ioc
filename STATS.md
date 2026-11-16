# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5291 attackers** · **1,178,611 hostile actions** · covering 65 day(s) through 2026-11-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 299 |
| Used a planted canary credential | 193 |
| Seen on more than one sensor | 444 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10726 |
| `ssh-bruteforce` | 1594 |
| `ssh-exploit` | 1402 |
| `redis-exploit` | 980 |
| `mcp-abuse` | 304 |
| `litellm-key-replay` | 178 |
| `docker-abuse` | 162 |
| `ollama-abuse` | 145 |
| `llamacpp-abuse` | 125 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 24 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3137 |
| `redis` | 1012 |
| `mcp` | 524 |
| `llamacpp` | 423 |
| `litellm` | 331 |
| `vllm` | 324 |
| `docker` | 287 |
| `jupyter` | 273 |
| `ollama` | 255 |
| `hfhub` | 216 |
| `php` | 152 |
| `ray` | 47 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1742 |
| `345gs5662d34` | 1098 |
| `admin` | 888 |
| `ubuntu` | 415 |
| `ftpuser` | 214 |
| `user` | 207 |
| `guest` | 192 |
| `test` | 167 |
| `ftp` | 128 |
| `git` | 119 |
| `deploy` | 116 |
| `postgres` | 111 |
| `administrator` | 106 |
| `config` | 103 |
| `bin` | 95 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 963 |
| `123` | 602 |
| `1234` | 466 |
| `12345678` | 384 |
| `admin` | 367 |
| `12345` | 297 |
| `1` | 279 |
| `admin123` | 232 |
| `P@ssw0rd` | 225 |
| `password` | 174 |
| `123456789` | 143 |
| `000000` | 135 |
| `!QAZ2wsx` | 128 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1516 |
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
| `INFO` | 699 |
| `PING` | 534 |
| `canary_env` | 428 |


_Generated from first-party honeypot capture. CC BY 4.0._
