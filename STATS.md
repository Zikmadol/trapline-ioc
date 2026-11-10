# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4580 attackers** · **1,048,716 hostile actions** · covering 59 day(s) through 2026-11-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 229 |
| Used a planted canary credential | 158 |
| Seen on more than one sensor | 358 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 8460 |
| `ssh-exploit` | 1389 |
| `ssh-bruteforce` | 1192 |
| `redis-exploit` | 894 |
| `mcp-abuse` | 292 |
| `litellm-key-replay` | 161 |
| `ollama-abuse` | 122 |
| `llamacpp-abuse` | 111 |
| `docker-abuse` | 66 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 21 |
| `php-abuse` | 20 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2698 |
| `redis` | 922 |
| `mcp` | 489 |
| `llamacpp` | 368 |
| `litellm` | 291 |
| `vllm` | 248 |
| `jupyter` | 241 |
| `ollama` | 213 |
| `hfhub` | 181 |
| `docker` | 173 |
| `php` | 113 |
| `ray` | 41 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1647 |
| `345gs5662d34` | 1098 |
| `admin` | 813 |
| `ubuntu` | 408 |
| `ftpuser` | 201 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 143 |
| `git` | 117 |
| `ftp` | 114 |
| `deploy` | 113 |
| `postgres` | 109 |
| `administrator` | 105 |
| `oracle` | 90 |
| `AdminGPON` | 86 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 932 |
| `123` | 597 |
| `1234` | 437 |
| `12345678` | 361 |
| `admin` | 334 |
| `12345` | 276 |
| `1` | 269 |
| `admin123` | 210 |
| `P@ssw0rd` | 210 |
| `password` | 160 |
| `000000` | 134 |
| `123456789` | 133 |
| `!QAZ2wsx` | 120 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1506 |
| `cd` | 1299 |
| `cat` | 1297 |
| `echo` | 1270 |
| `crontab` | 1243 |
| `lscpu` | 1240 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 635 |
| `PING` | 480 |
| `canary_env` | 397 |


_Generated from first-party honeypot capture. CC BY 4.0._
