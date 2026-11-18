# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5709 attackers** · **1,225,043 hostile actions** · covering 67 day(s) through 2026-11-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 314 |
| Used a planted canary credential | 236 |
| Seen on more than one sensor | 475 |
| Stage-2 hosts named in payloads | 64 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 12301 |
| `ssh-bruteforce` | 1833 |
| `ssh-exploit` | 1439 |
| `redis-exploit` | 1017 |
| `mcp-abuse` | 320 |
| `docker-abuse` | 183 |
| `litellm-key-replay` | 180 |
| `ollama-abuse` | 153 |
| `llamacpp-abuse` | 134 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3421 |
| `redis` | 1049 |
| `mcp` | 554 |
| `llamacpp` | 455 |
| `litellm` | 345 |
| `vllm` | 344 |
| `docker` | 316 |
| `jupyter` | 283 |
| `ollama` | 274 |
| `hfhub` | 230 |
| `php` | 164 |
| `ray` | 51 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1859 |
| `345gs5662d34` | 1103 |
| `admin` | 914 |
| `ubuntu` | 423 |
| `guest` | 225 |
| `ftpuser` | 220 |
| `user` | 217 |
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
| `1234` | 493 |
| `12345678` | 392 |
| `admin` | 387 |
| `12345` | 324 |
| `1` | 284 |
| `P@ssw0rd` | 242 |
| `admin123` | 237 |
| `password` | 175 |
| `123456789` | 145 |
| `000000` | 139 |
| `1111` | 134 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1561 |
| `cat` | 1343 |
| `cd` | 1337 |
| `echo` | 1317 |
| `crontab` | 1284 |
| `lscpu` | 1279 |
| `ls` | 1170 |
| `whoami` | 1165 |
| `free` | 1164 |
| `df` | 1162 |
| `top` | 1160 |
| `w` | 1160 |
| `INFO` | 717 |
| `PING` | 552 |
| `canary_env` | 449 |


_Generated from first-party honeypot capture. CC BY 4.0._
