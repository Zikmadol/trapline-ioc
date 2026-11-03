# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4128 attackers** · **839,016 hostile actions** · covering 52 day(s) through 2026-11-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 216 |
| Used a planted canary credential | 95 |
| Seen on more than one sensor | 304 |
| Stage-2 hosts named in payloads | 56 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6034 |
| `ssh-exploit` | 1365 |
| `ssh-bruteforce` | 1138 |
| `redis-exploit` | 723 |
| `mcp-abuse` | 272 |
| `litellm-key-replay` | 120 |
| `llamacpp-abuse` | 94 |
| `ollama-abuse` | 91 |
| `docker-abuse` | 57 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 17 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2599 |
| `redis` | 746 |
| `mcp` | 429 |
| `llamacpp` | 307 |
| `litellm` | 228 |
| `vllm` | 192 |
| `jupyter` | 186 |
| `ollama` | 152 |
| `hfhub` | 146 |
| `docker` | 144 |
| `php` | 84 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1608 |
| `345gs5662d34` | 1098 |
| `admin` | 775 |
| `ubuntu` | 393 |
| `user` | 190 |
| `ftpuser` | 187 |
| `test` | 148 |
| `guest` | 127 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `administrator` | 102 |
| `ftp` | 100 |
| `oracle` | 88 |
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
| `free` | 1126 |
| `whoami` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 495 |
| `canary_env` | 358 |
| `PING` | 354 |


_Generated from first-party honeypot capture. CC BY 4.0._
