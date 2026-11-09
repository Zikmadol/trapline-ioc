# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4513 attackers** · **1,026,663 hostile actions** · covering 58 day(s) through 2026-11-09

| signal | count |
|---|---|
| GPU / AI-hardware probing | 225 |
| Used a planted canary credential | 153 |
| Seen on more than one sensor | 349 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7896 |
| `ssh-exploit` | 1387 |
| `ssh-bruteforce` | 1185 |
| `redis-exploit` | 859 |
| `mcp-abuse` | 289 |
| `litellm-key-replay` | 158 |
| `ollama-abuse` | 121 |
| `llamacpp-abuse` | 107 |
| `docker-abuse` | 65 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `php-abuse` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2688 |
| `redis` | 885 |
| `mcp` | 480 |
| `llamacpp` | 359 |
| `litellm` | 284 |
| `vllm` | 241 |
| `jupyter` | 235 |
| `ollama` | 207 |
| `hfhub` | 179 |
| `docker` | 168 |
| `php` | 108 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1644 |
| `345gs5662d34` | 1098 |
| `admin` | 807 |
| `ubuntu` | 408 |
| `ftpuser` | 198 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 140 |
| `git` | 117 |
| `deploy` | 113 |
| `ftp` | 111 |
| `postgres` | 108 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 85 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 928 |
| `123` | 597 |
| `1234` | 430 |
| `12345678` | 358 |
| `admin` | 329 |
| `12345` | 273 |
| `1` | 268 |
| `admin123` | 207 |
| `P@ssw0rd` | 207 |
| `password` | 160 |
| `123456789` | 133 |
| `000000` | 132 |
| `!QAZ2wsx` | 119 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1504 |
| `cd` | 1299 |
| `cat` | 1297 |
| `echo` | 1268 |
| `crontab` | 1241 |
| `lscpu` | 1238 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 604 |
| `PING` | 451 |
| `canary_env` | 390 |


_Generated from first-party honeypot capture. CC BY 4.0._
