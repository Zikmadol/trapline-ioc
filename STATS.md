# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5893 attackers** · **1,287,483 hostile actions** · covering 70 day(s) through 2026-11-21

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
| `ssh-bruteforce` | 1901 |
| `ssh-exploit` | 1457 |
| `redis-exploit` | 1057 |
| `mcp-abuse` | 330 |
| `docker-abuse` | 192 |
| `litellm-key-replay` | 186 |
| `ollama-abuse` | 161 |
| `llamacpp-abuse` | 136 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 27 |
| `php-abuse` | 27 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3512 |
| `redis` | 1089 |
| `mcp` | 573 |
| `llamacpp` | 475 |
| `vllm` | 361 |
| `litellm` | 361 |
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
| `admin` | 931 |
| `ubuntu` | 432 |
| `guest` | 232 |
| `ftpuser` | 225 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 140 |
| `deploy` | 127 |
| `config` | 125 |
| `git` | 125 |
| `administrator` | 114 |
| `postgres` | 114 |
| `support` | 114 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1026 |
| `123` | 627 |
| `1234` | 510 |
| `12345678` | 401 |
| `admin` | 398 |
| `12345` | 344 |
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
| `uname` | 1588 |
| `cat` | 1365 |
| `cd` | 1360 |
| `echo` | 1337 |
| `crontab` | 1303 |
| `lscpu` | 1297 |
| `ls` | 1188 |
| `free` | 1182 |
| `whoami` | 1182 |
| `df` | 1179 |
| `top` | 1178 |
| `w` | 1178 |
| `INFO` | 747 |
| `PING` | 574 |
| `canary_env` | 461 |


_Generated from first-party honeypot capture. CC BY 4.0._
