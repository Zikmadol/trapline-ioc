# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4311 attackers** · **887,197 hostile actions** · covering 55 day(s) through 2026-11-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 219 |
| Used a planted canary credential | 143 |
| Seen on more than one sensor | 324 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6714 |
| `ssh-exploit` | 1374 |
| `ssh-bruteforce` | 1164 |
| `redis-exploit` | 768 |
| `mcp-abuse` | 280 |
| `litellm-key-replay` | 139 |
| `ollama-abuse` | 105 |
| `llamacpp-abuse` | 102 |
| `docker-abuse` | 60 |
| `jupyter-abuse` | 39 |
| `vllm-abuse` | 18 |
| `llamacpp-key-replay` | 17 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2640 |
| `redis` | 793 |
| `mcp` | 455 |
| `llamacpp` | 333 |
| `litellm` | 257 |
| `vllm` | 207 |
| `jupyter` | 206 |
| `ollama` | 178 |
| `hfhub` | 162 |
| `docker` | 157 |
| `php` | 94 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1627 |
| `345gs5662d34` | 1098 |
| `admin` | 792 |
| `ubuntu` | 402 |
| `user` | 194 |
| `ftpuser` | 193 |
| `test` | 150 |
| `guest` | 135 |
| `git` | 116 |
| `deploy` | 113 |
| `postgres` | 108 |
| `ftp` | 106 |
| `administrator` | 102 |
| `oracle` | 90 |
| `AdminGPON` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 918 |
| `123` | 593 |
| `1234` | 424 |
| `12345678` | 348 |
| `admin` | 317 |
| `12345` | 269 |
| `1` | 267 |
| `P@ssw0rd` | 202 |
| `admin123` | 198 |
| `password` | 160 |
| `123456789` | 133 |
| `000000` | 129 |
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
| `INFO` | 529 |
| `PING` | 383 |
| `canary_env` | 377 |


_Generated from first-party honeypot capture. CC BY 4.0._
