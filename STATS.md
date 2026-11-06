# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4306 attackers** · **887,109 hostile actions** · covering 55 day(s) through 2026-11-06

| signal | count |
|---|---|
| GPU / AI-hardware probing | 218 |
| Used a planted canary credential | 143 |
| Seen on more than one sensor | 324 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6700 |
| `ssh-exploit` | 1374 |
| `ssh-bruteforce` | 1163 |
| `redis-exploit` | 766 |
| `mcp-abuse` | 280 |
| `litellm-key-replay` | 139 |
| `ollama-abuse` | 104 |
| `llamacpp-abuse` | 102 |
| `docker-abuse` | 59 |
| `jupyter-abuse` | 39 |
| `vllm-abuse` | 18 |
| `llamacpp-key-replay` | 17 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2639 |
| `redis` | 791 |
| `mcp` | 455 |
| `llamacpp` | 333 |
| `litellm` | 257 |
| `vllm` | 207 |
| `jupyter` | 205 |
| `ollama` | 177 |
| `hfhub` | 162 |
| `docker` | 156 |
| `php` | 94 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1626 |
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
| `INFO` | 527 |
| `PING` | 382 |
| `canary_env` | 377 |


_Generated from first-party honeypot capture. CC BY 4.0._
