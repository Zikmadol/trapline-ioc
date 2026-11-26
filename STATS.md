# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6322 attackers** · **1,374,738 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 343 |
| Used a planted canary credential | 270 |
| Seen on more than one sensor | 516 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13586 |
| `ssh-bruteforce` | 1958 |
| `ssh-exploit` | 1471 |
| `redis-exploit` | 1151 |
| `mcp-abuse` | 360 |
| `llamacpp-abuse` | 225 |
| `docker-abuse` | 223 |
| `litellm-key-replay` | 207 |
| `ollama-abuse` | 169 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 34 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3594 |
| `redis` | 1183 |
| `mcp` | 709 |
| `llamacpp` | 624 |
| `vllm` | 495 |
| `litellm` | 433 |
| `docker` | 375 |
| `jupyter` | 333 |
| `ollama` | 305 |
| `hfhub` | 265 |
| `php` | 199 |
| `ray` | 75 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1950 |
| `345gs5662d34` | 1107 |
| `admin` | 957 |
| `ubuntu` | 441 |
| `guest` | 241 |
| `ftpuser` | 235 |
| `user` | 222 |
| `test` | 175 |
| `ftp` | 149 |
| `config` | 134 |
| `deploy` | 130 |
| `git` | 126 |
| `bin` | 118 |
| `administrator` | 117 |
| `george` | 116 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1096 |
| `123456` | 1045 |
| `123` | 637 |
| `1234` | 533 |
| `admin` | 419 |
| `12345678` | 410 |
| `12345` | 357 |
| `1` | 303 |
| `admin123` | 264 |
| `P@ssw0rd` | 256 |
| `password` | 173 |
| `1111` | 153 |
| `123456789` | 152 |
| `000000` | 147 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1614 |
| `cat` | 1384 |
| `cd` | 1379 |
| `echo` | 1352 |
| `crontab` | 1319 |
| `lscpu` | 1312 |
| `ls` | 1201 |
| `free` | 1195 |
| `whoami` | 1195 |
| `df` | 1192 |
| `top` | 1191 |
| `w` | 1191 |
| `INFO` | 813 |
| `PING` | 636 |
| `canary_env` | 596 |


_Generated from first-party honeypot capture. CC BY 4.0._
