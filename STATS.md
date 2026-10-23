# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3106 attackers** · **613,476 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 186 |
| Used a planted canary credential | 36 |
| Seen on more than one sensor | 222 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2937 |
| `ssh-exploit` | 1198 |
| `ssh-bruteforce` | 707 |
| `redis-exploit` | 575 |
| `mcp-abuse` | 237 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 59 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 33 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1982 |
| `redis` | 590 |
| `mcp` | 346 |
| `llamacpp` | 225 |
| `jupyter` | 136 |
| `vllm` | 133 |
| `litellm` | 124 |
| `ollama` | 102 |
| `hfhub` | 101 |
| `docker` | 94 |
| `ray` | 22 |
| `php` | 22 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1147 |
| `345gs5662d34` | 960 |
| `admin` | 665 |
| `ubuntu` | 314 |
| `user` | 161 |
| `ftpuser` | 159 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 99 |
| `administrator` | 93 |
| `oracle` | 74 |
| `ftp` | 73 |
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 958 |
| `3245gs5662d34` | 951 |
| `123456` | 775 |
| `123` | 508 |
| `1234` | 369 |
| `12345678` | 284 |
| `admin` | 245 |
| `12345` | 232 |
| `1` | 228 |
| `P@ssw0rd` | 168 |
| `password` | 156 |
| `admin123` | 150 |
| `000000` | 118 |
| `123456789` | 115 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1308 |
| `cd` | 1127 |
| `cat` | 1126 |
| `echo` | 1112 |
| `crontab` | 1090 |
| `lscpu` | 1088 |
| `ls` | 987 |
| `free` | 986 |
| `df` | 984 |
| `top` | 984 |
| `whoami` | 983 |
| `w` | 982 |
| `INFO` | 387 |
| `canary_env` | 295 |
| `PING` | 263 |


_Generated from first-party honeypot capture. CC BY 4.0._
