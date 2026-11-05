# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4269 attackers** · **878,407 hostile actions** · covering 54 day(s) through 2026-11-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 218 |
| Used a planted canary credential | 132 |
| Seen on more than one sensor | 322 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6525 |
| `ssh-exploit` | 1374 |
| `ssh-bruteforce` | 1156 |
| `redis-exploit` | 755 |
| `mcp-abuse` | 278 |
| `litellm-key-replay` | 134 |
| `llamacpp-abuse` | 102 |
| `ollama-abuse` | 102 |
| `docker-abuse` | 59 |
| `jupyter-abuse` | 39 |
| `vllm-abuse` | 18 |
| `llamacpp-key-replay` | 17 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2632 |
| `redis` | 780 |
| `mcp` | 449 |
| `llamacpp` | 330 |
| `litellm` | 250 |
| `vllm` | 204 |
| `jupyter` | 204 |
| `ollama` | 175 |
| `hfhub` | 162 |
| `docker` | 155 |
| `php` | 93 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1621 |
| `345gs5662d34` | 1098 |
| `admin` | 789 |
| `ubuntu` | 401 |
| `user` | 194 |
| `ftpuser` | 193 |
| `test` | 150 |
| `guest` | 134 |
| `git` | 116 |
| `deploy` | 113 |
| `postgres` | 108 |
| `ftp` | 105 |
| `administrator` | 102 |
| `oracle` | 90 |
| `AdminGPON` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 915 |
| `123` | 592 |
| `1234` | 423 |
| `12345678` | 346 |
| `admin` | 313 |
| `12345` | 268 |
| `1` | 267 |
| `P@ssw0rd` | 201 |
| `admin123` | 196 |
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
| `INFO` | 520 |
| `canary_env` | 374 |
| `PING` | 374 |


_Generated from first-party honeypot capture. CC BY 4.0._
