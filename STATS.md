# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5564 attackers** · **1,205,519 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 310 |
| Used a planted canary credential | 230 |
| Seen on more than one sensor | 467 |
| Stage-2 hosts named in payloads | 61 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11205 |
| `ssh-bruteforce` | 1747 |
| `ssh-exploit` | 1430 |
| `redis-exploit` | 1002 |
| `mcp-abuse` | 313 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 172 |
| `ollama-abuse` | 150 |
| `llamacpp-abuse` | 130 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3322 |
| `redis` | 1034 |
| `mcp` | 540 |
| `llamacpp` | 441 |
| `vllm` | 337 |
| `litellm` | 336 |
| `docker` | 304 |
| `jupyter` | 279 |
| `ollama` | 271 |
| `hfhub` | 224 |
| `php` | 161 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1812 |
| `345gs5662d34` | 1101 |
| `admin` | 899 |
| `ubuntu` | 422 |
| `guest` | 220 |
| `ftpuser` | 217 |
| `user` | 215 |
| `test` | 173 |
| `ftp` | 131 |
| `git` | 121 |
| `deploy` | 119 |
| `postgres` | 111 |
| `config` | 110 |
| `support` | 108 |
| `administrator` | 107 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1099 |
| `3245gs5662d34` | 1091 |
| `123456` | 989 |
| `123` | 611 |
| `1234` | 479 |
| `12345678` | 388 |
| `admin` | 377 |
| `12345` | 308 |
| `1` | 280 |
| `P@ssw0rd` | 236 |
| `admin123` | 235 |
| `password` | 172 |
| `123456789` | 144 |
| `000000` | 138 |
| `1111` | 130 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1545 |
| `cat` | 1329 |
| `cd` | 1323 |
| `echo` | 1303 |
| `crontab` | 1269 |
| `lscpu` | 1265 |
| `ls` | 1156 |
| `whoami` | 1151 |
| `free` | 1150 |
| `df` | 1148 |
| `top` | 1146 |
| `w` | 1146 |
| `INFO` | 713 |
| `PING` | 546 |
| `canary_env` | 440 |


_Generated from first-party honeypot capture. CC BY 4.0._
