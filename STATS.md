# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6376 attackers** · **1,381,933 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 344 |
| Used a planted canary credential | 276 |
| Seen on more than one sensor | 519 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13601 |
| `ssh-bruteforce` | 1968 |
| `ssh-exploit` | 1474 |
| `redis-exploit` | 1167 |
| `mcp-abuse` | 363 |
| `docker-abuse` | 230 |
| `llamacpp-abuse` | 225 |
| `litellm-key-replay` | 213 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3609 |
| `redis` | 1199 |
| `mcp` | 713 |
| `llamacpp` | 625 |
| `vllm` | 498 |
| `litellm` | 439 |
| `docker` | 383 |
| `jupyter` | 333 |
| `ollama` | 308 |
| `hfhub` | 267 |
| `php` | 202 |
| `ray` | 76 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1961 |
| `345gs5662d34` | 1107 |
| `admin` | 960 |
| `ubuntu` | 442 |
| `guest` | 242 |
| `ftpuser` | 236 |
| `user` | 223 |
| `test` | 175 |
| `ftp` | 151 |
| `config` | 136 |
| `deploy` | 132 |
| `git` | 126 |
| `administrator` | 119 |
| `bin` | 119 |
| `george` | 117 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1097 |
| `123456` | 1048 |
| `123` | 638 |
| `1234` | 540 |
| `admin` | 421 |
| `12345678` | 414 |
| `12345` | 358 |
| `1` | 303 |
| `admin123` | 265 |
| `P@ssw0rd` | 257 |
| `password` | 174 |
| `1111` | 153 |
| `123456789` | 152 |
| `000000` | 148 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1618 |
| `cat` | 1388 |
| `cd` | 1383 |
| `echo` | 1355 |
| `crontab` | 1322 |
| `lscpu` | 1315 |
| `ls` | 1204 |
| `free` | 1198 |
| `whoami` | 1198 |
| `df` | 1195 |
| `top` | 1194 |
| `w` | 1194 |
| `INFO` | 828 |
| `PING` | 651 |
| `canary_env` | 600 |


_Generated from first-party honeypot capture. CC BY 4.0._
