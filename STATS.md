# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6297 attackers** · **1,371,952 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 342 |
| Used a planted canary credential | 269 |
| Seen on more than one sensor | 516 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13585 |
| `ssh-bruteforce` | 1957 |
| `ssh-exploit` | 1470 |
| `redis-exploit` | 1148 |
| `mcp-abuse` | 351 |
| `llamacpp-abuse` | 225 |
| `docker-abuse` | 222 |
| `litellm-key-replay` | 206 |
| `ollama-abuse` | 169 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 33 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3592 |
| `redis` | 1180 |
| `mcp` | 699 |
| `llamacpp` | 623 |
| `vllm` | 491 |
| `litellm` | 432 |
| `docker` | 374 |
| `jupyter` | 327 |
| `ollama` | 304 |
| `hfhub` | 265 |
| `php` | 199 |
| `ray` | 69 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1948 |
| `345gs5662d34` | 1107 |
| `admin` | 957 |
| `ubuntu` | 441 |
| `guest` | 241 |
| `ftpuser` | 235 |
| `user` | 222 |
| `test` | 175 |
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
| `123456` | 1043 |
| `123` | 637 |
| `1234` | 532 |
| `admin` | 419 |
| `12345678` | 410 |
| `12345` | 357 |
| `1` | 303 |
| `admin123` | 264 |
| `P@ssw0rd` | 256 |
| `password` | 172 |
| `1111` | 153 |
| `123456789` | 151 |
| `000000` | 147 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1611 |
| `cat` | 1382 |
| `cd` | 1377 |
| `echo` | 1350 |
| `crontab` | 1317 |
| `lscpu` | 1310 |
| `ls` | 1199 |
| `free` | 1193 |
| `whoami` | 1193 |
| `df` | 1190 |
| `top` | 1189 |
| `w` | 1189 |
| `INFO` | 811 |
| `PING` | 635 |
| `canary_env` | 595 |


_Generated from first-party honeypot capture. CC BY 4.0._
