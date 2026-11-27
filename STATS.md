# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6469 attackers** · **1,395,718 hostile actions** · covering 76 day(s) through 2026-11-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 348 |
| Used a planted canary credential | 277 |
| Seen on more than one sensor | 527 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13609 |
| `ssh-bruteforce` | 2001 |
| `ssh-exploit` | 1480 |
| `redis-exploit` | 1201 |
| `mcp-abuse` | 365 |
| `docker-abuse` | 233 |
| `litellm-key-replay` | 226 |
| `llamacpp-abuse` | 225 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3649 |
| `redis` | 1233 |
| `mcp` | 717 |
| `llamacpp` | 632 |
| `vllm` | 502 |
| `litellm` | 457 |
| `docker` | 391 |
| `jupyter` | 339 |
| `ollama` | 310 |
| `hfhub` | 269 |
| `php` | 207 |
| `ray` | 78 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1994 |
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
| `git` | 126 |
| `bin` | 121 |
| `administrator` | 119 |
| `george` | 119 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1097 |
| `123456` | 1053 |
| `123` | 644 |
| `1234` | 542 |
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
| `uname` | 1629 |
| `cat` | 1399 |
| `cd` | 1393 |
| `echo` | 1365 |
| `crontab` | 1333 |
| `lscpu` | 1325 |
| `ls` | 1214 |
| `free` | 1208 |
| `whoami` | 1208 |
| `df` | 1205 |
| `top` | 1204 |
| `w` | 1204 |
| `INFO` | 859 |
| `PING` | 682 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
