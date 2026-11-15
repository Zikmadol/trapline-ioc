# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5236 attackers** · **1,176,664 hostile actions** · covering 64 day(s) through 2026-11-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 299 |
| Used a planted canary credential | 193 |
| Seen on more than one sensor | 441 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10565 |
| `ssh-bruteforce` | 1550 |
| `ssh-exploit` | 1403 |
| `redis-exploit` | 976 |
| `mcp-abuse` | 303 |
| `litellm-key-replay` | 177 |
| `docker-abuse` | 161 |
| `ollama-abuse` | 143 |
| `llamacpp-abuse` | 124 |
| `jupyter-abuse` | 50 |
| `php-abuse` | 24 |
| `vllm-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3093 |
| `redis` | 1008 |
| `mcp` | 522 |
| `llamacpp` | 417 |
| `litellm` | 328 |
| `vllm` | 321 |
| `docker` | 286 |
| `jupyter` | 270 |
| `ollama` | 253 |
| `hfhub` | 215 |
| `php` | 151 |
| `ray` | 47 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1732 |
| `345gs5662d34` | 1098 |
| `admin` | 885 |
| `ubuntu` | 415 |
| `ftpuser` | 214 |
| `user` | 207 |
| `guest` | 188 |
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
| `123456` | 962 |
| `123` | 602 |
| `1234` | 466 |
| `12345678` | 384 |
| `admin` | 363 |
| `12345` | 297 |
| `1` | 278 |
| `admin123` | 232 |
| `P@ssw0rd` | 225 |
| `password` | 174 |
| `123456789` | 143 |
| `000000` | 135 |
| `1111` | 127 |

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
| `INFO` | 695 |
| `PING` | 532 |
| `canary_env` | 423 |


_Generated from first-party honeypot capture. CC BY 4.0._
