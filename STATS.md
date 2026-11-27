# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6478 attackers** · **1,396,028 hostile actions** · covering 76 day(s) through 2026-11-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 349 |
| Used a planted canary credential | 277 |
| Seen on more than one sensor | 528 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13609 |
| `ssh-bruteforce` | 2005 |
| `ssh-exploit` | 1481 |
| `redis-exploit` | 1203 |
| `mcp-abuse` | 365 |
| `docker-abuse` | 233 |
| `litellm-key-replay` | 227 |
| `llamacpp-abuse` | 225 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 59 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3654 |
| `redis` | 1235 |
| `mcp` | 717 |
| `llamacpp` | 634 |
| `vllm` | 503 |
| `litellm` | 458 |
| `docker` | 391 |
| `jupyter` | 341 |
| `ollama` | 311 |
| `hfhub` | 270 |
| `php` | 208 |
| `ray` | 79 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1996 |
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
| `123456` | 1055 |
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
| `uname` | 1632 |
| `cat` | 1402 |
| `cd` | 1396 |
| `echo` | 1368 |
| `crontab` | 1336 |
| `lscpu` | 1328 |
| `ls` | 1217 |
| `free` | 1211 |
| `whoami` | 1211 |
| `df` | 1208 |
| `top` | 1207 |
| `w` | 1207 |
| `INFO` | 861 |
| `PING` | 684 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
