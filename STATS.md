# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3986 attackers** · **778,275 hostile actions** · covering 50 day(s) through 2026-11-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 209 |
| Used a planted canary credential | 61 |
| Seen on more than one sensor | 285 |
| Stage-2 hosts named in payloads | 55 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5406 |
| `ssh-exploit` | 1353 |
| `ssh-bruteforce` | 1126 |
| `redis-exploit` | 687 |
| `mcp-abuse` | 268 |
| `litellm-key-replay` | 106 |
| `llamacpp-abuse` | 89 |
| `ollama-abuse` | 80 |
| `docker-abuse` | 54 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 15 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2570 |
| `redis` | 706 |
| `mcp` | 413 |
| `llamacpp` | 283 |
| `litellm` | 202 |
| `vllm` | 177 |
| `jupyter` | 174 |
| `docker` | 137 |
| `ollama` | 134 |
| `hfhub` | 130 |
| `php` | 69 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1598 |
| `345gs5662d34` | 1098 |
| `admin` | 757 |
| `ubuntu` | 383 |
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
| `123456` | 894 |
| `123` | 584 |
| `1234` | 415 |
| `12345678` | 333 |
| `admin` | 294 |
| `1` | 263 |
| `12345` | 262 |
| `P@ssw0rd` | 193 |
| `admin123` | 183 |
| `password` | 157 |
| `123456789` | 131 |
| `000000` | 125 |
| `!QAZ2wsx` | 110 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1475 |
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
| `INFO` | 466 |
| `canary_env` | 347 |
| `PING` | 332 |


_Generated from first-party honeypot capture. CC BY 4.0._
