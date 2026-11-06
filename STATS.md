# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4350 attackers** · **892,299 hostile actions** · covering 55 day(s) through 2026-11-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 220 |
| Used a planted canary credential | 148 |
| Seen on more than one sensor | 326 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6820 |
| `ssh-exploit` | 1374 |
| `ssh-bruteforce` | 1168 |
| `redis-exploit` | 775 |
| `mcp-abuse` | 280 |
| `litellm-key-replay` | 148 |
| `ollama-abuse` | 107 |
| `llamacpp-abuse` | 102 |
| `docker-abuse` | 59 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 17 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2645 |
| `redis` | 800 |
| `mcp` | 458 |
| `llamacpp` | 336 |
| `litellm` | 267 |
| `jupyter` | 220 |
| `vllm` | 215 |
| `ollama` | 183 |
| `hfhub` | 164 |
| `docker` | 158 |
| `php` | 94 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1630 |
| `345gs5662d34` | 1098 |
| `admin` | 793 |
| `ubuntu` | 402 |
| `user` | 194 |
| `ftpuser` | 193 |
| `test` | 150 |
| `guest` | 135 |
| `git` | 117 |
| `deploy` | 113 |
| `postgres` | 108 |
| `ftp` | 106 |
| `administrator` | 103 |
| `oracle` | 90 |
| `AdminGPON` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 918 |
| `123` | 594 |
| `1234` | 425 |
| `12345678` | 349 |
| `admin` | 318 |
| `12345` | 270 |
| `1` | 268 |
| `P@ssw0rd` | 202 |
| `admin123` | 198 |
| `password` | 160 |
| `123456789` | 134 |
| `000000` | 130 |
| `!QAZ2wsx` | 113 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1493 |
| `cd` | 1291 |
| `cat` | 1289 |
| `echo` | 1266 |
| `crontab` | 1240 |
| `lscpu` | 1237 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 535 |
| `PING` | 388 |
| `canary_env` | 379 |


_Generated from first-party honeypot capture. CC BY 4.0._
