# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3909 attackers** · **755,758 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 207 |
| Used a planted canary credential | 54 |
| Seen on more than one sensor | 278 |
| Stage-2 hosts named in payloads | 52 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4947 |
| `ssh-exploit` | 1349 |
| `ssh-bruteforce` | 1105 |
| `redis-exploit` | 676 |
| `mcp-abuse` | 265 |
| `litellm-key-replay` | 96 |
| `llamacpp-abuse` | 88 |
| `ollama-abuse` | 77 |
| `docker-abuse` | 51 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2542 |
| `redis` | 695 |
| `mcp` | 406 |
| `llamacpp` | 268 |
| `litellm` | 188 |
| `vllm` | 172 |
| `jupyter` | 171 |
| `docker` | 132 |
| `ollama` | 130 |
| `hfhub` | 126 |
| `php` | 64 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1581 |
| `345gs5662d34` | 1098 |
| `admin` | 740 |
| `ubuntu` | 370 |
| `user` | 185 |
| `ftpuser` | 183 |
| `test` | 140 |
| `guest` | 119 |
| `git` | 114 |
| `deploy` | 112 |
| `postgres` | 109 |
| `administrator` | 99 |
| `ftp` | 94 |
| `oracle` | 83 |
| `debian` | 77 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 880 |
| `123` | 578 |
| `1234` | 410 |
| `12345678` | 325 |
| `admin` | 287 |
| `1` | 258 |
| `12345` | 257 |
| `P@ssw0rd` | 191 |
| `admin123` | 179 |
| `password` | 158 |
| `123456789` | 127 |
| `000000` | 125 |
| `!QAZ2wsx` | 109 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1468 |
| `cd` | 1277 |
| `cat` | 1275 |
| `echo` | 1261 |
| `crontab` | 1235 |
| `lscpu` | 1233 |
| `ls` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `whoami` | 1122 |
| `INFO` | 459 |
| `canary_env` | 341 |
| `PING` | 327 |


_Generated from first-party honeypot capture. CC BY 4.0._
