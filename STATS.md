# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5855 attackers** · **1,280,590 hostile actions** · covering 70 day(s) through 2026-11-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 321 |
| Used a planted canary credential | 246 |
| Seen on more than one sensor | 486 |
| Stage-2 hosts named in payloads | 67 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13508 |
| `ssh-bruteforce` | 1885 |
| `ssh-exploit` | 1456 |
| `redis-exploit` | 1050 |
| `mcp-abuse` | 327 |
| `docker-abuse` | 189 |
| `litellm-key-replay` | 186 |
| `ollama-abuse` | 158 |
| `llamacpp-abuse` | 136 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 26 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3494 |
| `redis` | 1082 |
| `mcp` | 569 |
| `llamacpp` | 467 |
| `litellm` | 360 |
| `vllm` | 358 |
| `docker` | 326 |
| `jupyter` | 294 |
| `ollama` | 282 |
| `hfhub` | 238 |
| `php` | 172 |
| `ray` | 56 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1896 |
| `345gs5662d34` | 1105 |
| `admin` | 930 |
| `ubuntu` | 430 |
| `guest` | 231 |
| `ftpuser` | 225 |
| `user` | 218 |
| `test` | 173 |
| `ftp` | 139 |
| `deploy` | 127 |
| `git` | 125 |
| `config` | 124 |
| `support` | 115 |
| `postgres` | 114 |
| `administrator` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1102 |
| `3245gs5662d34` | 1094 |
| `123456` | 1020 |
| `123` | 627 |
| `1234` | 507 |
| `12345678` | 400 |
| `admin` | 397 |
| `12345` | 341 |
| `1` | 293 |
| `admin123` | 248 |
| `P@ssw0rd` | 246 |
| `password` | 171 |
| `123456789` | 148 |
| `1111` | 143 |
| `000000` | 142 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1583 |
| `cat` | 1361 |
| `cd` | 1356 |
| `echo` | 1333 |
| `crontab` | 1299 |
| `lscpu` | 1293 |
| `ls` | 1184 |
| `free` | 1178 |
| `whoami` | 1178 |
| `df` | 1175 |
| `top` | 1174 |
| `w` | 1174 |
| `INFO` | 742 |
| `PING` | 572 |
| `canary_env` | 458 |


_Generated from first-party honeypot capture. CC BY 4.0._
