# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4186 attackers** · **855,705 hostile actions** · covering 53 day(s) through 2026-11-04

| signal | count |
|---|---|
| GPU / AI-hardware probing | 217 |
| Used a planted canary credential | 110 |
| Seen on more than one sensor | 312 |
| Stage-2 hosts named in payloads | 57 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6253 |
| `ssh-exploit` | 1365 |
| `ssh-bruteforce` | 1148 |
| `redis-exploit` | 735 |
| `mcp-abuse` | 275 |
| `litellm-key-replay` | 125 |
| `llamacpp-abuse` | 98 |
| `ollama-abuse` | 97 |
| `docker-abuse` | 57 |
| `jupyter-abuse` | 39 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2610 |
| `redis` | 758 |
| `mcp` | 439 |
| `llamacpp` | 316 |
| `litellm` | 234 |
| `vllm` | 195 |
| `jupyter` | 193 |
| `ollama` | 163 |
| `hfhub` | 152 |
| `docker` | 149 |
| `php` | 88 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1614 |
| `345gs5662d34` | 1098 |
| `admin` | 783 |
| `ubuntu` | 396 |
| `user` | 193 |
| `ftpuser` | 190 |
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
| `123456` | 909 |
| `123` | 588 |
| `1234` | 420 |
| `12345678` | 341 |
| `admin` | 309 |
| `12345` | 266 |
| `1` | 265 |
| `P@ssw0rd` | 199 |
| `admin123` | 192 |
| `password` | 159 |
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
| `INFO` | 503 |
| `canary_env` | 364 |
| `PING` | 362 |


_Generated from first-party honeypot capture. CC BY 4.0._
