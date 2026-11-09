# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4501 attackers** · **1,021,459 hostile actions** · covering 58 day(s) through 2026-11-09

| signal | count |
|---|---|
| GPU / AI-hardware probing | 225 |
| Used a planted canary credential | 153 |
| Seen on more than one sensor | 348 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7839 |
| `ssh-exploit` | 1387 |
| `ssh-bruteforce` | 1183 |
| `redis-exploit` | 854 |
| `mcp-abuse` | 288 |
| `litellm-key-replay` | 155 |
| `ollama-abuse` | 120 |
| `llamacpp-abuse` | 107 |
| `docker-abuse` | 65 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `php-abuse` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2685 |
| `redis` | 880 |
| `mcp` | 477 |
| `llamacpp` | 358 |
| `litellm` | 281 |
| `vllm` | 239 |
| `jupyter` | 234 |
| `ollama` | 205 |
| `hfhub` | 178 |
| `docker` | 167 |
| `php` | 106 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1643 |
| `345gs5662d34` | 1098 |
| `admin` | 806 |
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
| `admin` | 328 |
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
| `INFO` | 599 |
| `PING` | 447 |
| `canary_env` | 389 |


_Generated from first-party honeypot capture. CC BY 4.0._
