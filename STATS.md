# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5896 attackers** · **1,289,858 hostile actions** · covering 70 day(s) through 2026-11-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 323 |
| Used a planted canary credential | 246 |
| Seen on more than one sensor | 492 |
| Stage-2 hosts named in payloads | 68 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13508 |
| `ssh-bruteforce` | 1902 |
| `ssh-exploit` | 1457 |
| `redis-exploit` | 1058 |
| `mcp-abuse` | 330 |
| `docker-abuse` | 192 |
| `litellm-key-replay` | 188 |
| `ollama-abuse` | 161 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 27 |
| `php-abuse` | 27 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3513 |
| `redis` | 1090 |
| `mcp` | 574 |
| `llamacpp` | 476 |
| `litellm` | 363 |
| `vllm` | 362 |
| `docker` | 332 |
| `jupyter` | 298 |
| `ollama` | 286 |
| `hfhub` | 241 |
| `php` | 176 |
| `ray` | 56 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1908 |
| `345gs5662d34` | 1106 |
| `admin` | 932 |
| `ubuntu` | 433 |
| `guest` | 232 |
| `ftpuser` | 225 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 140 |
| `deploy` | 127 |
| `config` | 125 |
| `git` | 125 |
| `administrator` | 115 |
| `support` | 114 |
| `postgres` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1026 |
| `123` | 627 |
| `1234` | 511 |
| `12345678` | 401 |
| `admin` | 398 |
| `12345` | 345 |
| `1` | 295 |
| `admin123` | 248 |
| `P@ssw0rd` | 247 |
| `password` | 172 |
| `123456789` | 149 |
| `1111` | 144 |
| `000000` | 143 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1589 |
| `cat` | 1366 |
| `cd` | 1361 |
| `echo` | 1338 |
| `crontab` | 1304 |
| `lscpu` | 1298 |
| `ls` | 1189 |
| `free` | 1183 |
| `whoami` | 1183 |
| `df` | 1180 |
| `top` | 1179 |
| `w` | 1179 |
| `INFO` | 748 |
| `PING` | 575 |
| `canary_env` | 461 |


_Generated from first-party honeypot capture. CC BY 4.0._
