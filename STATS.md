# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3995 attackers** · **782,632 hostile actions** · covering 50 day(s) through 2026-11-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 209 |
| Used a planted canary credential | 63 |
| Seen on more than one sensor | 286 |
| Stage-2 hosts named in payloads | 55 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5450 |
| `ssh-exploit` | 1353 |
| `ssh-bruteforce` | 1127 |
| `redis-exploit` | 690 |
| `mcp-abuse` | 269 |
| `litellm-key-replay` | 106 |
| `llamacpp-abuse` | 91 |
| `ollama-abuse` | 80 |
| `docker-abuse` | 54 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 15 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2572 |
| `redis` | 709 |
| `mcp` | 415 |
| `llamacpp` | 286 |
| `litellm` | 204 |
| `vllm` | 178 |
| `jupyter` | 176 |
| `docker` | 137 |
| `ollama` | 134 |
| `hfhub` | 133 |
| `php` | 69 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1597 |
| `345gs5662d34` | 1098 |
| `admin` | 758 |
| `ubuntu` | 384 |
| `user` | 186 |
| `ftpuser` | 184 |
| `test` | 145 |
| `guest` | 122 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 109 |
| `administrator` | 100 |
| `ftp` | 98 |
| `oracle` | 84 |
| `debian` | 78 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 895 |
| `123` | 584 |
| `1234` | 415 |
| `12345678` | 334 |
| `admin` | 294 |
| `1` | 263 |
| `12345` | 262 |
| `P@ssw0rd` | 193 |
| `admin123` | 184 |
| `password` | 157 |
| `123456789` | 132 |
| `000000` | 125 |
| `!QAZ2wsx` | 110 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1476 |
| `cd` | 1280 |
| `cat` | 1278 |
| `echo` | 1261 |
| `crontab` | 1236 |
| `lscpu` | 1233 |
| `ls` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `whoami` | 1123 |
| `w` | 1122 |
| `INFO` | 468 |
| `canary_env` | 349 |
| `PING` | 334 |


_Generated from first-party honeypot capture. CC BY 4.0._
