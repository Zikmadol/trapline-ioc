# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6348 attackers** · **1,380,752 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 343 |
| Used a planted canary credential | 274 |
| Seen on more than one sensor | 516 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13590 |
| `ssh-bruteforce` | 1962 |
| `ssh-exploit` | 1474 |
| `redis-exploit` | 1159 |
| `mcp-abuse` | 361 |
| `llamacpp-abuse` | 225 |
| `docker-abuse` | 224 |
| `litellm-key-replay` | 210 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3602 |
| `redis` | 1191 |
| `mcp` | 711 |
| `llamacpp` | 625 |
| `vllm` | 496 |
| `litellm` | 436 |
| `docker` | 376 |
| `jupyter` | 333 |
| `ollama` | 308 |
| `hfhub` | 267 |
| `php` | 200 |
| `ray` | 76 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1956 |
| `345gs5662d34` | 1107 |
| `admin` | 959 |
| `ubuntu` | 441 |
| `guest` | 242 |
| `ftpuser` | 236 |
| `user` | 223 |
| `test` | 175 |
| `ftp` | 150 |
| `config` | 136 |
| `deploy` | 132 |
| `git` | 126 |
| `bin` | 119 |
| `administrator` | 117 |
| `george` | 117 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1096 |
| `123456` | 1048 |
| `123` | 637 |
| `1234` | 537 |
| `admin` | 421 |
| `12345678` | 414 |
| `12345` | 358 |
| `1` | 303 |
| `admin123` | 264 |
| `P@ssw0rd` | 257 |
| `password` | 175 |
| `1111` | 153 |
| `123456789` | 152 |
| `000000` | 148 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1616 |
| `cat` | 1386 |
| `cd` | 1381 |
| `echo` | 1354 |
| `crontab` | 1321 |
| `lscpu` | 1314 |
| `ls` | 1203 |
| `free` | 1197 |
| `whoami` | 1197 |
| `df` | 1194 |
| `top` | 1193 |
| `w` | 1193 |
| `INFO` | 821 |
| `PING` | 643 |
| `canary_env` | 598 |


_Generated from first-party honeypot capture. CC BY 4.0._
