# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5398 attackers** · **1,192,873 hostile actions** · covering 65 day(s) through 2026-11-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 300 |
| Used a planted canary credential | 198 |
| Seen on more than one sensor | 452 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10978 |
| `ssh-bruteforce` | 1666 |
| `ssh-exploit` | 1409 |
| `redis-exploit` | 991 |
| `mcp-abuse` | 307 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 163 |
| `ollama-abuse` | 148 |
| `llamacpp-abuse` | 127 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 25 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3219 |
| `redis` | 1023 |
| `mcp` | 531 |
| `llamacpp` | 428 |
| `litellm` | 334 |
| `vllm` | 326 |
| `docker` | 291 |
| `jupyter` | 276 |
| `ollama` | 262 |
| `hfhub` | 220 |
| `php` | 156 |
| `ray` | 48 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1768 |
| `345gs5662d34` | 1099 |
| `admin` | 894 |
| `ubuntu` | 418 |
| `ftpuser` | 215 |
| `user` | 214 |
| `guest` | 208 |
| `test` | 171 |
| `ftp` | 129 |
| `git` | 120 |
| `deploy` | 117 |
| `postgres` | 111 |
| `config` | 108 |
| `administrator` | 106 |
| `support` | 103 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1097 |
| `3245gs5662d34` | 1089 |
| `123456` | 971 |
| `123` | 608 |
| `1234` | 468 |
| `12345678` | 385 |
| `admin` | 370 |
| `12345` | 298 |
| `1` | 278 |
| `admin123` | 233 |
| `P@ssw0rd` | 230 |
| `password` | 174 |
| `123456789` | 144 |
| `000000` | 136 |
| `1111` | 128 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1525 |
| `cat` | 1310 |
| `cd` | 1306 |
| `echo` | 1283 |
| `crontab` | 1252 |
| `lscpu` | 1249 |
| `ls` | 1138 |
| `whoami` | 1135 |
| `free` | 1133 |
| `df` | 1131 |
| `top` | 1130 |
| `w` | 1129 |
| `INFO` | 707 |
| `PING` | 540 |
| `canary_env` | 432 |


_Generated from first-party honeypot capture. CC BY 4.0._
