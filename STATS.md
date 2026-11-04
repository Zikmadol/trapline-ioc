# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4213 attackers** · **858,979 hostile actions** · covering 53 day(s) through 2026-11-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 218 |
| Used a planted canary credential | 128 |
| Seen on more than one sensor | 315 |
| Stage-2 hosts named in payloads | 57 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6321 |
| `ssh-exploit` | 1366 |
| `ssh-bruteforce` | 1148 |
| `redis-exploit` | 740 |
| `mcp-abuse` | 276 |
| `litellm-key-replay` | 127 |
| `llamacpp-abuse` | 98 |
| `ollama-abuse` | 97 |
| `docker-abuse` | 57 |
| `jupyter-abuse` | 39 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2613 |
| `redis` | 763 |
| `mcp` | 442 |
| `llamacpp` | 318 |
| `litellm` | 239 |
| `vllm` | 197 |
| `jupyter` | 193 |
| `ollama` | 164 |
| `hfhub` | 154 |
| `docker` | 150 |
| `php` | 89 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1615 |
| `345gs5662d34` | 1098 |
| `admin` | 783 |
| `ubuntu` | 396 |
| `user` | 193 |
| `ftpuser` | 191 |
| `test` | 150 |
| `guest` | 132 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `ftp` | 103 |
| `administrator` | 102 |
| `oracle` | 90 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 911 |
| `123` | 589 |
| `1234` | 421 |
| `12345678` | 341 |
| `admin` | 309 |
| `1` | 267 |
| `12345` | 266 |
| `P@ssw0rd` | 199 |
| `admin123` | 192 |
| `password` | 159 |
| `123456789` | 133 |
| `000000` | 129 |
| `!QAZ2wsx` | 113 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1485 |
| `cd` | 1284 |
| `cat` | 1282 |
| `echo` | 1266 |
| `crontab` | 1240 |
| `lscpu` | 1237 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 507 |
| `canary_env` | 365 |
| `PING` | 365 |


_Generated from first-party honeypot capture. CC BY 4.0._
