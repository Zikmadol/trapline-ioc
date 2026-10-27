# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3520 attackers** · **696,166 hostile actions** · covering 45 day(s) through 2026-10-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 194 |
| Used a planted canary credential | 40 |
| Seen on more than one sensor | 258 |
| Stage-2 hosts named in payloads | 45 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3649 |
| `ssh-exploit` | 1253 |
| `ssh-bruteforce` | 961 |
| `redis-exploit` | 626 |
| `mcp-abuse` | 250 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 70 |
| `litellm-key-replay` | 61 |
| `docker-abuse` | 45 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2295 |
| `redis` | 642 |
| `mcp` | 371 |
| `llamacpp` | 240 |
| `jupyter` | 158 |
| `vllm` | 150 |
| `litellm` | 141 |
| `ollama` | 115 |
| `docker` | 112 |
| `hfhub` | 111 |
| `php` | 50 |
| `ray` | 27 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1418 |
| `345gs5662d34` | 1009 |
| `admin` | 700 |
| `ubuntu` | 341 |
| `user` | 170 |
| `ftpuser` | 169 |
| `test` | 138 |
| `deploy` | 112 |
| `git` | 111 |
| `guest` | 109 |
| `postgres` | 103 |
| `administrator` | 96 |
| `ftp` | 82 |
| `oracle` | 76 |
| `AdminGPON` | 70 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1007 |
| `3245gs5662d34` | 999 |
| `123456` | 821 |
| `123` | 517 |
| `1234` | 388 |
| `12345678` | 305 |
| `admin` | 269 |
| `1` | 243 |
| `12345` | 243 |
| `P@ssw0rd` | 179 |
| `admin123` | 164 |
| `password` | 151 |
| `000000` | 123 |
| `123456789` | 122 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1371 |
| `cd` | 1180 |
| `cat` | 1179 |
| `echo` | 1165 |
| `crontab` | 1141 |
| `lscpu` | 1139 |
| `ls` | 1035 |
| `free` | 1034 |
| `df` | 1032 |
| `top` | 1032 |
| `whoami` | 1031 |
| `w` | 1030 |
| `INFO` | 421 |
| `canary_env` | 315 |
| `PING` | 296 |


_Generated from first-party honeypot capture. CC BY 4.0._
