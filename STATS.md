# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3140 attackers** · **620,064 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 36 |
| Seen on more than one sensor | 225 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3002 |
| `ssh-exploit` | 1206 |
| `ssh-bruteforce` | 726 |
| `redis-exploit` | 580 |
| `mcp-abuse` | 238 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 60 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 33 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2009 |
| `redis` | 595 |
| `mcp` | 347 |
| `llamacpp` | 226 |
| `jupyter` | 138 |
| `vllm` | 134 |
| `litellm` | 126 |
| `ollama` | 102 |
| `hfhub` | 101 |
| `docker` | 95 |
| `php` | 25 |
| `ray` | 22 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1168 |
| `345gs5662d34` | 965 |
| `admin` | 668 |
| `ubuntu` | 315 |
| `user` | 162 |
| `ftpuser` | 161 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 100 |
| `administrator` | 93 |
| `ftp` | 74 |
| `oracle` | 74 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 963 |
| `3245gs5662d34` | 956 |
| `123456` | 782 |
| `123` | 508 |
| `1234` | 370 |
| `12345678` | 286 |
| `admin` | 246 |
| `12345` | 232 |
| `1` | 228 |
| `P@ssw0rd` | 169 |
| `password` | 156 |
| `admin123` | 154 |
| `000000` | 118 |
| `123456789` | 116 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1315 |
| `cd` | 1133 |
| `cat` | 1132 |
| `echo` | 1117 |
| `crontab` | 1095 |
| `lscpu` | 1093 |
| `ls` | 992 |
| `free` | 991 |
| `df` | 989 |
| `top` | 989 |
| `whoami` | 988 |
| `w` | 987 |
| `INFO` | 391 |
| `canary_env` | 296 |
| `PING` | 266 |


_Generated from first-party honeypot capture. CC BY 4.0._
