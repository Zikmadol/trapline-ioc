# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5165 attackers** · **1,167,133 hostile actions** · covering 64 day(s) through 2026-11-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 294 |
| Used a planted canary credential | 187 |
| Seen on more than one sensor | 438 |
| Stage-2 hosts named in payloads | 61 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10360 |
| `ssh-bruteforce` | 1504 |
| `ssh-exploit` | 1402 |
| `redis-exploit` | 969 |
| `mcp-abuse` | 303 |
| `litellm-key-replay` | 176 |
| `docker-abuse` | 156 |
| `ollama-abuse` | 142 |
| `llamacpp-abuse` | 121 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3043 |
| `redis` | 1001 |
| `mcp` | 521 |
| `llamacpp` | 410 |
| `litellm` | 325 |
| `vllm` | 317 |
| `docker` | 280 |
| `jupyter` | 266 |
| `ollama` | 252 |
| `hfhub` | 213 |
| `php` | 150 |
| `ray` | 47 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1723 |
| `345gs5662d34` | 1098 |
| `admin` | 880 |
| `ubuntu` | 415 |
| `ftpuser` | 212 |
| `user` | 205 |
| `guest` | 177 |
| `test` | 165 |
| `ftp` | 126 |
| `git` | 119 |
| `deploy` | 116 |
| `postgres` | 111 |
| `administrator` | 106 |
| `config` | 100 |
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
| `admin` | 357 |
| `12345` | 295 |
| `1` | 277 |
| `admin123` | 230 |
| `P@ssw0rd` | 223 |
| `password` | 174 |
| `123456789` | 143 |
| `000000` | 135 |
| `!QAZ2wsx` | 127 |

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
| `INFO` | 691 |
| `PING` | 527 |
| `canary_env` | 420 |


_Generated from first-party honeypot capture. CC BY 4.0._
