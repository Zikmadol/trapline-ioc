# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6274 attackers** · **1,368,445 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 342 |
| Used a planted canary credential | 269 |
| Seen on more than one sensor | 514 |
| Stage-2 hosts named in payloads | 73 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13585 |
| `ssh-bruteforce` | 1948 |
| `ssh-exploit` | 1471 |
| `redis-exploit` | 1141 |
| `mcp-abuse` | 349 |
| `llamacpp-abuse` | 222 |
| `docker-abuse` | 222 |
| `litellm-key-replay` | 206 |
| `ollama-abuse` | 169 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 32 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3583 |
| `redis` | 1173 |
| `mcp` | 694 |
| `llamacpp` | 618 |
| `vllm` | 487 |
| `litellm` | 431 |
| `docker` | 373 |
| `jupyter` | 327 |
| `ollama` | 301 |
| `hfhub` | 264 |
| `php` | 197 |
| `ray` | 69 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1941 |
| `345gs5662d34` | 1107 |
| `admin` | 955 |
| `ubuntu` | 441 |
| `guest` | 241 |
| `ftpuser` | 234 |
| `user` | 222 |
| `test` | 174 |
| `ftp` | 149 |
| `config` | 134 |
| `deploy` | 129 |
| `git` | 126 |
| `bin` | 118 |
| `administrator` | 117 |
| `george` | 116 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1096 |
| `123456` | 1042 |
| `123` | 636 |
| `1234` | 530 |
| `admin` | 418 |
| `12345678` | 410 |
| `12345` | 356 |
| `1` | 303 |
| `admin123` | 264 |
| `P@ssw0rd` | 256 |
| `password` | 174 |
| `1111` | 153 |
| `123456789` | 151 |
| `000000` | 147 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1609 |
| `cat` | 1380 |
| `cd` | 1375 |
| `echo` | 1348 |
| `crontab` | 1315 |
| `lscpu` | 1308 |
| `ls` | 1197 |
| `free` | 1191 |
| `whoami` | 1191 |
| `df` | 1188 |
| `top` | 1187 |
| `w` | 1187 |
| `INFO` | 806 |
| `PING` | 630 |
| `canary_env` | 589 |


_Generated from first-party honeypot capture. CC BY 4.0._
