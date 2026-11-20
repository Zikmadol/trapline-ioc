# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5786 attackers** · **1,252,913 hostile actions** · covering 69 day(s) through 2026-11-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 316 |
| Used a planted canary credential | 241 |
| Seen on more than one sensor | 482 |
| Stage-2 hosts named in payloads | 66 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13370 |
| `ssh-bruteforce` | 1858 |
| `ssh-exploit` | 1449 |
| `redis-exploit` | 1035 |
| `mcp-abuse` | 324 |
| `docker-abuse` | 185 |
| `litellm-key-replay` | 184 |
| `ollama-abuse` | 155 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 25 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3458 |
| `redis` | 1067 |
| `mcp` | 563 |
| `llamacpp` | 460 |
| `litellm` | 356 |
| `vllm` | 354 |
| `docker` | 321 |
| `jupyter` | 289 |
| `ollama` | 278 |
| `hfhub` | 235 |
| `php` | 167 |
| `ray` | 54 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1880 |
| `345gs5662d34` | 1105 |
| `admin` | 917 |
| `ubuntu` | 425 |
| `guest` | 228 |
| `ftpuser` | 222 |
| `user` | 218 |
| `test` | 174 |
| `ftp` | 136 |
| `deploy` | 124 |
| `git` | 123 |
| `config` | 121 |
| `support` | 114 |
| `administrator` | 111 |
| `postgres` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1102 |
| `3245gs5662d34` | 1094 |
| `123456` | 1011 |
| `123` | 616 |
| `1234` | 501 |
| `12345678` | 395 |
| `admin` | 391 |
| `12345` | 332 |
| `1` | 289 |
| `P@ssw0rd` | 244 |
| `admin123` | 240 |
| `password` | 174 |
| `123456789` | 146 |
| `000000` | 141 |
| `1111` | 141 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1574 |
| `cat` | 1354 |
| `cd` | 1347 |
| `echo` | 1329 |
| `crontab` | 1295 |
| `lscpu` | 1290 |
| `ls` | 1180 |
| `whoami` | 1175 |
| `free` | 1174 |
| `df` | 1172 |
| `top` | 1170 |
| `w` | 1170 |
| `INFO` | 730 |
| `PING` | 561 |
| `canary_env` | 455 |


_Generated from first-party honeypot capture. CC BY 4.0._
