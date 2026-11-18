# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5707 attackers** · **1,219,924 hostile actions** · covering 67 day(s) through 2026-11-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 314 |
| Used a planted canary credential | 236 |
| Seen on more than one sensor | 475 |
| Stage-2 hosts named in payloads | 64 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 12229 |
| `ssh-bruteforce` | 1834 |
| `ssh-exploit` | 1437 |
| `redis-exploit` | 1017 |
| `mcp-abuse` | 320 |
| `docker-abuse` | 183 |
| `litellm-key-replay` | 180 |
| `ollama-abuse` | 153 |
| `llamacpp-abuse` | 133 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3420 |
| `redis` | 1049 |
| `mcp` | 554 |
| `llamacpp` | 454 |
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
| `root` | 1858 |
| `345gs5662d34` | 1103 |
| `admin` | 913 |
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
| `123456` | 1001 |
| `123` | 614 |
| `1234` | 493 |
| `12345678` | 392 |
| `admin` | 387 |
| `12345` | 324 |
| `1` | 283 |
| `P@ssw0rd` | 242 |
| `admin123` | 237 |
| `password` | 176 |
| `123456789` | 145 |
| `000000` | 139 |
| `1111` | 134 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1560 |
| `cat` | 1342 |
| `cd` | 1336 |
| `echo` | 1316 |
| `crontab` | 1283 |
| `lscpu` | 1278 |
| `ls` | 1169 |
| `whoami` | 1164 |
| `free` | 1163 |
| `df` | 1161 |
| `top` | 1159 |
| `w` | 1159 |
| `INFO` | 717 |
| `PING` | 552 |
| `canary_env` | 449 |


_Generated from first-party honeypot capture. CC BY 4.0._
