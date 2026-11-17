# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5581 attackers** · **1,206,503 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 310 |
| Used a planted canary credential | 230 |
| Seen on more than one sensor | 468 |
| Stage-2 hosts named in payloads | 62 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11238 |
| `ssh-bruteforce` | 1760 |
| `ssh-exploit` | 1430 |
| `redis-exploit` | 1003 |
| `mcp-abuse` | 315 |
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
| `ssh` | 3336 |
| `redis` | 1035 |
| `mcp` | 543 |
| `llamacpp` | 442 |
| `vllm` | 340 |
| `litellm` | 336 |
| `docker` | 304 |
| `jupyter` | 280 |
| `ollama` | 271 |
| `hfhub` | 225 |
| `php` | 161 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1817 |
| `345gs5662d34` | 1101 |
| `admin` | 900 |
| `ubuntu` | 423 |
| `guest` | 221 |
| `ftpuser` | 218 |
| `user` | 215 |
| `test` | 173 |
| `ftp` | 132 |
| `git` | 122 |
| `deploy` | 119 |
| `config` | 111 |
| `postgres` | 111 |
| `support` | 110 |
| `administrator` | 108 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1099 |
| `3245gs5662d34` | 1091 |
| `123456` | 990 |
| `123` | 612 |
| `1234` | 481 |
| `12345678` | 389 |
| `admin` | 379 |
| `12345` | 310 |
| `1` | 280 |
| `P@ssw0rd` | 237 |
| `admin123` | 236 |
| `password` | 172 |
| `123456789` | 144 |
| `000000` | 138 |
| `1111` | 131 |

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
| `canary_env` | 442 |


_Generated from first-party honeypot capture. CC BY 4.0._
