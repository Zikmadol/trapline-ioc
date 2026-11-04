# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4171 attackers** · **851,509 hostile actions** · covering 53 day(s) through 2026-11-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 217 |
| Used a planted canary credential | 107 |
| Seen on more than one sensor | 308 |
| Stage-2 hosts named in payloads | 57 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6206 |
| `ssh-exploit` | 1365 |
| `ssh-bruteforce` | 1146 |
| `redis-exploit` | 731 |
| `mcp-abuse` | 275 |
| `litellm-key-replay` | 124 |
| `llamacpp-abuse` | 96 |
| `ollama-abuse` | 95 |
| `docker-abuse` | 57 |
| `jupyter-abuse` | 39 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2608 |
| `redis` | 754 |
| `mcp` | 437 |
| `llamacpp` | 312 |
| `litellm` | 233 |
| `vllm` | 194 |
| `jupyter` | 189 |
| `ollama` | 160 |
| `hfhub` | 149 |
| `docker` | 147 |
| `php` | 87 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1613 |
| `345gs5662d34` | 1098 |
| `admin` | 780 |
| `ubuntu` | 395 |
| `user` | 192 |
| `ftpuser` | 189 |
| `test` | 150 |
| `guest` | 131 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `administrator` | 102 |
| `ftp` | 102 |
| `oracle` | 90 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 906 |
| `123` | 588 |
| `1234` | 419 |
| `12345678` | 340 |
| `admin` | 308 |
| `1` | 265 |
| `12345` | 265 |
| `P@ssw0rd` | 198 |
| `admin123` | 191 |
| `password` | 158 |
| `123456789` | 133 |
| `000000` | 129 |
| `!QAZ2wsx` | 113 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1484 |
| `cd` | 1284 |
| `cat` | 1282 |
| `echo` | 1265 |
| `crontab` | 1239 |
| `lscpu` | 1236 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 501 |
| `canary_env` | 364 |
| `PING` | 359 |


_Generated from first-party honeypot capture. CC BY 4.0._
