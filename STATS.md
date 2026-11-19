# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5718 attackers** · **1,226,081 hostile actions** · covering 68 day(s) through 2026-11-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 314 |
| Used a planted canary credential | 237 |
| Seen on more than one sensor | 475 |
| Stage-2 hosts named in payloads | 65 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 12408 |
| `ssh-bruteforce` | 1838 |
| `ssh-exploit` | 1440 |
| `redis-exploit` | 1017 |
| `mcp-abuse` | 320 |
| `docker-abuse` | 183 |
| `litellm-key-replay` | 180 |
| `ollama-abuse` | 154 |
| `llamacpp-abuse` | 134 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3427 |
| `redis` | 1049 |
| `mcp` | 554 |
| `llamacpp` | 455 |
| `litellm` | 345 |
| `vllm` | 344 |
| `docker` | 316 |
| `jupyter` | 283 |
| `ollama` | 275 |
| `hfhub` | 230 |
| `php` | 165 |
| `ray` | 51 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1864 |
| `345gs5662d34` | 1103 |
| `admin` | 914 |
| `ubuntu` | 424 |
| `guest` | 225 |
| `ftpuser` | 220 |
| `user` | 218 |
| `test` | 174 |
| `ftp` | 134 |
| `deploy` | 124 |
| `git` | 123 |
| `config` | 119 |
| `support` | 113 |
| `postgres` | 112 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1100 |
| `3245gs5662d34` | 1092 |
| `123456` | 1002 |
| `123` | 614 |
| `1234` | 494 |
| `12345678` | 392 |
| `admin` | 387 |
| `12345` | 325 |
| `1` | 284 |
| `P@ssw0rd` | 242 |
| `admin123` | 237 |
| `password` | 175 |
| `123456789` | 146 |
| `000000` | 139 |
| `1111` | 134 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1563 |
| `cat` | 1344 |
| `cd` | 1338 |
| `echo` | 1318 |
| `crontab` | 1285 |
| `lscpu` | 1280 |
| `ls` | 1171 |
| `whoami` | 1166 |
| `free` | 1165 |
| `df` | 1163 |
| `top` | 1161 |
| `w` | 1161 |
| `INFO` | 717 |
| `PING` | 552 |
| `canary_env` | 449 |


_Generated from first-party honeypot capture. CC BY 4.0._
