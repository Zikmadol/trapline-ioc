# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4661 attackers** · **1,061,801 hostile actions** · covering 61 day(s) through 2026-11-12

| signal | count |
|---|---|
| GPU / AI-hardware probing | 234 |
| Used a planted canary credential | 171 |
| Seen on more than one sensor | 370 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9019 |
| `ssh-exploit` | 1393 |
| `ssh-bruteforce` | 1207 |
| `redis-exploit` | 918 |
| `mcp-abuse` | 296 |
| `litellm-key-replay` | 164 |
| `ollama-abuse` | 125 |
| `llamacpp-abuse` | 113 |
| `docker-abuse` | 72 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 21 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2722 |
| `redis` | 947 |
| `mcp` | 501 |
| `llamacpp` | 378 |
| `litellm` | 294 |
| `vllm` | 259 |
| `jupyter` | 244 |
| `ollama` | 220 |
| `hfhub` | 184 |
| `docker` | 179 |
| `php` | 121 |
| `ray` | 43 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1659 |
| `345gs5662d34` | 1098 |
| `admin` | 823 |
| `ubuntu` | 410 |
| `ftpuser` | 205 |
| `user` | 194 |
| `test` | 152 |
| `guest` | 146 |
| `git` | 117 |
| `ftp` | 117 |
| `deploy` | 114 |
| `postgres` | 109 |
| `administrator` | 106 |
| `oracle` | 90 |
| `AdminGPON` | 87 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 938 |
| `123` | 598 |
| `1234` | 441 |
| `12345678` | 365 |
| `admin` | 338 |
| `12345` | 280 |
| `1` | 272 |
| `admin123` | 214 |
| `P@ssw0rd` | 213 |
| `password` | 161 |
| `123456789` | 134 |
| `000000` | 134 |
| `!QAZ2wsx` | 121 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1512 |
| `cat` | 1299 |
| `cd` | 1299 |
| `echo` | 1274 |
| `crontab` | 1245 |
| `lscpu` | 1242 |
| `ls` | 1130 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 654 |
| `PING` | 499 |
| `canary_env` | 403 |


_Generated from first-party honeypot capture. CC BY 4.0._
