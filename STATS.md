# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5402 attackers** · **1,193,159 hostile actions** · covering 65 day(s) through 2026-11-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 301 |
| Used a planted canary credential | 198 |
| Seen on more than one sensor | 453 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10978 |
| `ssh-bruteforce` | 1669 |
| `ssh-exploit` | 1409 |
| `redis-exploit` | 991 |
| `mcp-abuse` | 308 |
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
| `ssh` | 3222 |
| `redis` | 1023 |
| `mcp` | 534 |
| `llamacpp` | 428 |
| `litellm` | 334 |
| `vllm` | 326 |
| `docker` | 291 |
| `jupyter` | 276 |
| `ollama` | 262 |
| `hfhub` | 220 |
| `php` | 157 |
| `ray` | 48 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1771 |
| `345gs5662d34` | 1099 |
| `admin` | 895 |
| `ubuntu` | 419 |
| `ftpuser` | 215 |
| `user` | 214 |
| `guest` | 209 |
| `test` | 173 |
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
| `123456` | 973 |
| `123` | 608 |
| `1234` | 468 |
| `12345678` | 385 |
| `admin` | 370 |
| `12345` | 298 |
| `1` | 278 |
| `admin123` | 233 |
| `P@ssw0rd` | 232 |
| `password` | 174 |
| `123456789` | 144 |
| `000000` | 136 |
| `1111` | 128 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1526 |
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
| `w` | 1130 |
| `INFO` | 707 |
| `PING` | 540 |
| `canary_env` | 433 |


_Generated from first-party honeypot capture. CC BY 4.0._
