# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4674 attackers** · **1,088,799 hostile actions** · covering 61 day(s) through 2026-11-12

| signal | count |
|---|---|
| GPU / AI-hardware probing | 234 |
| Used a planted canary credential | 172 |
| Seen on more than one sensor | 374 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9149 |
| `ssh-exploit` | 1394 |
| `ssh-bruteforce` | 1210 |
| `redis-exploit` | 922 |
| `mcp-abuse` | 296 |
| `litellm-key-replay` | 165 |
| `ollama-abuse` | 126 |
| `llamacpp-abuse` | 113 |
| `docker-abuse` | 73 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 24 |
| `php-abuse` | 21 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2729 |
| `redis` | 951 |
| `mcp` | 503 |
| `llamacpp` | 379 |
| `litellm` | 297 |
| `vllm` | 262 |
| `jupyter` | 244 |
| `ollama` | 221 |
| `hfhub` | 191 |
| `docker` | 180 |
| `php` | 124 |
| `ray` | 43 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1661 |
| `345gs5662d34` | 1098 |
| `admin` | 825 |
| `ubuntu` | 410 |
| `ftpuser` | 206 |
| `user` | 194 |
| `test` | 152 |
| `guest` | 147 |
| `ftp` | 118 |
| `git` | 117 |
| `deploy` | 114 |
| `postgres` | 109 |
| `administrator` | 106 |
| `oracle` | 90 |
| `AdminGPON` | 88 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 939 |
| `123` | 598 |
| `1234` | 442 |
| `12345678` | 366 |
| `admin` | 340 |
| `12345` | 281 |
| `1` | 271 |
| `admin123` | 215 |
| `P@ssw0rd` | 214 |
| `password` | 161 |
| `123456789` | 134 |
| `000000` | 133 |
| `!QAZ2wsx` | 123 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1512 |
| `cat` | 1299 |
| `cd` | 1299 |
| `echo` | 1275 |
| `crontab` | 1245 |
| `lscpu` | 1242 |
| `ls` | 1130 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 658 |
| `PING` | 501 |
| `canary_env` | 404 |


_Generated from first-party honeypot capture. CC BY 4.0._
