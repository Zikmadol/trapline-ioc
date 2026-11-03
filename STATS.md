# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4135 attackers** · **841,987 hostile actions** · covering 52 day(s) through 2026-11-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 216 |
| Used a planted canary credential | 97 |
| Seen on more than one sensor | 305 |
| Stage-2 hosts named in payloads | 56 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6066 |
| `ssh-exploit` | 1365 |
| `ssh-bruteforce` | 1139 |
| `redis-exploit` | 726 |
| `mcp-abuse` | 272 |
| `litellm-key-replay` | 120 |
| `llamacpp-abuse` | 94 |
| `ollama-abuse` | 91 |
| `docker-abuse` | 58 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 17 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2600 |
| `redis` | 749 |
| `mcp` | 431 |
| `llamacpp` | 309 |
| `litellm` | 228 |
| `vllm` | 193 |
| `jupyter` | 187 |
| `ollama` | 154 |
| `hfhub` | 146 |
| `docker` | 145 |
| `php` | 85 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1609 |
| `345gs5662d34` | 1098 |
| `admin` | 776 |
| `ubuntu` | 394 |
| `user` | 191 |
| `ftpuser` | 187 |
| `test` | 149 |
| `guest` | 128 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `administrator` | 102 |
| `ftp` | 100 |
| `oracle` | 89 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 903 |
| `123` | 588 |
| `1234` | 417 |
| `12345678` | 338 |
| `admin` | 303 |
| `1` | 265 |
| `12345` | 263 |
| `P@ssw0rd` | 196 |
| `admin123` | 189 |
| `password` | 157 |
| `123456789` | 132 |
| `000000` | 129 |
| `!QAZ2wsx` | 113 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1483 |
| `cd` | 1284 |
| `cat` | 1282 |
| `echo` | 1265 |
| `crontab` | 1239 |
| `lscpu` | 1236 |
| `ls` | 1128 |
| `whoami` | 1127 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 496 |
| `canary_env` | 359 |
| `PING` | 354 |


_Generated from first-party honeypot capture. CC BY 4.0._
