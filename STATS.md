# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4519 attackers** · **1,028,713 hostile actions** · covering 58 day(s) through 2026-11-09

| signal | count |
|---|---|
| GPU / AI-hardware probing | 225 |
| Used a planted canary credential | 153 |
| Seen on more than one sensor | 349 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7927 |
| `ssh-exploit` | 1387 |
| `ssh-bruteforce` | 1186 |
| `redis-exploit` | 861 |
| `mcp-abuse` | 289 |
| `litellm-key-replay` | 158 |
| `ollama-abuse` | 122 |
| `llamacpp-abuse` | 108 |
| `docker-abuse` | 65 |
| `jupyter-abuse` | 50 |
| `php-abuse` | 19 |
| `vllm-abuse` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2689 |
| `redis` | 887 |
| `mcp` | 480 |
| `llamacpp` | 360 |
| `litellm` | 284 |
| `vllm` | 241 |
| `jupyter` | 235 |
| `ollama` | 208 |
| `hfhub` | 179 |
| `docker` | 168 |
| `php` | 109 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1644 |
| `345gs5662d34` | 1098 |
| `admin` | 808 |
| `ubuntu` | 408 |
| `ftpuser` | 199 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 141 |
| `git` | 117 |
| `deploy` | 113 |
| `ftp` | 112 |
| `postgres` | 108 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 85 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 929 |
| `123` | 597 |
| `1234` | 431 |
| `12345678` | 359 |
| `admin` | 330 |
| `12345` | 274 |
| `1` | 269 |
| `admin123` | 208 |
| `P@ssw0rd` | 208 |
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
| `INFO` | 606 |
| `PING` | 452 |
| `canary_env` | 390 |


_Generated from first-party honeypot capture. CC BY 4.0._
