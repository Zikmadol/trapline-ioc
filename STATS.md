# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3921 attackers** · **756,628 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 207 |
| Used a planted canary credential | 54 |
| Seen on more than one sensor | 278 |
| Stage-2 hosts named in payloads | 52 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4978 |
| `ssh-exploit` | 1351 |
| `ssh-bruteforce` | 1105 |
| `redis-exploit` | 677 |
| `mcp-abuse` | 266 |
| `litellm-key-replay` | 100 |
| `llamacpp-abuse` | 88 |
| `ollama-abuse` | 77 |
| `docker-abuse` | 51 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2544 |
| `redis` | 696 |
| `mcp` | 407 |
| `llamacpp` | 273 |
| `litellm` | 194 |
| `jupyter` | 173 |
| `vllm` | 172 |
| `docker` | 132 |
| `ollama` | 130 |
| `hfhub` | 127 |
| `php` | 64 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1581 |
| `345gs5662d34` | 1098 |
| `admin` | 740 |
| `ubuntu` | 372 |
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
| `123456` | 882 |
| `123` | 580 |
| `1234` | 410 |
| `12345678` | 327 |
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
| `uname` | 1470 |
| `cd` | 1279 |
| `cat` | 1277 |
| `echo` | 1261 |
| `crontab` | 1235 |
| `lscpu` | 1233 |
| `ls` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `whoami` | 1122 |
| `INFO` | 460 |
| `canary_env` | 342 |
| `PING` | 327 |


_Generated from first-party honeypot capture. CC BY 4.0._
