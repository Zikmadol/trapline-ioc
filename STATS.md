# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5958 attackers** · **1,314,753 hostile actions** · covering 71 day(s) through 2026-11-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 328 |
| Used a planted canary credential | 250 |
| Seen on more than one sensor | 498 |
| Stage-2 hosts named in payloads | 69 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13519 |
| `ssh-bruteforce` | 1907 |
| `ssh-exploit` | 1461 |
| `redis-exploit` | 1075 |
| `mcp-abuse` | 333 |
| `docker-abuse` | 210 |
| `litellm-key-replay` | 188 |
| `ollama-abuse` | 162 |
| `llamacpp-abuse` | 141 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 29 |
| `php-abuse` | 27 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3524 |
| `redis` | 1107 |
| `mcp` | 580 |
| `llamacpp` | 489 |
| `vllm` | 370 |
| `litellm` | 368 |
| `docker` | 352 |
| `jupyter` | 304 |
| `ollama` | 289 |
| `hfhub` | 247 |
| `php` | 181 |
| `ray` | 57 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1910 |
| `345gs5662d34` | 1106 |
| `admin` | 938 |
| `ubuntu` | 434 |
| `guest` | 234 |
| `ftpuser` | 227 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 142 |
| `deploy` | 129 |
| `config` | 127 |
| `git` | 125 |
| `administrator` | 116 |
| `support` | 114 |
| `postgres` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1030 |
| `123` | 630 |
| `1234` | 515 |
| `12345678` | 404 |
| `admin` | 402 |
| `12345` | 348 |
| `1` | 297 |
| `admin123` | 251 |
| `P@ssw0rd` | 249 |
| `password` | 172 |
| `123456789` | 150 |
| `1111` | 146 |
| `000000` | 144 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1594 |
| `cat` | 1369 |
| `cd` | 1364 |
| `echo` | 1339 |
| `crontab` | 1306 |
| `lscpu` | 1299 |
| `ls` | 1189 |
| `free` | 1183 |
| `whoami` | 1183 |
| `df` | 1180 |
| `top` | 1179 |
| `w` | 1179 |
| `INFO` | 760 |
| `PING` | 587 |
| `canary_env` | 469 |


_Generated from first-party honeypot capture. CC BY 4.0._
