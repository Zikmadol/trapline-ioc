# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6491 attackers** · **1,396,252 hostile actions** · covering 76 day(s) through 2026-11-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 349 |
| Used a planted canary credential | 277 |
| Seen on more than one sensor | 529 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13609 |
| `ssh-bruteforce` | 2011 |
| `ssh-exploit` | 1484 |
| `redis-exploit` | 1205 |
| `mcp-abuse` | 365 |
| `docker-abuse` | 233 |
| `llamacpp-abuse` | 227 |
| `litellm-key-replay` | 227 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 59 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3664 |
| `redis` | 1238 |
| `mcp` | 719 |
| `llamacpp` | 637 |
| `vllm` | 504 |
| `litellm` | 458 |
| `docker` | 392 |
| `jupyter` | 342 |
| `ollama` | 312 |
| `hfhub` | 271 |
| `php` | 209 |
| `ray` | 79 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 2002 |
| `345gs5662d34` | 1107 |
| `admin` | 966 |
| `ubuntu` | 441 |
| `guest` | 245 |
| `ftpuser` | 239 |
| `user` | 227 |
| `test` | 178 |
| `ftp` | 153 |
| `config` | 138 |
| `deploy` | 132 |
| `git` | 127 |
| `bin` | 121 |
| `administrator` | 119 |
| `george` | 119 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1097 |
| `123456` | 1057 |
| `123` | 644 |
| `1234` | 543 |
| `admin` | 424 |
| `12345678` | 416 |
| `12345` | 360 |
| `1` | 303 |
| `admin123` | 267 |
| `P@ssw0rd` | 260 |
| `password` | 176 |
| `1111` | 155 |
| `123456789` | 152 |
| `000000` | 149 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1635 |
| `cat` | 1405 |
| `cd` | 1398 |
| `echo` | 1371 |
| `crontab` | 1338 |
| `lscpu` | 1330 |
| `ls` | 1220 |
| `free` | 1213 |
| `whoami` | 1213 |
| `df` | 1210 |
| `top` | 1209 |
| `w` | 1209 |
| `INFO` | 863 |
| `PING` | 686 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
