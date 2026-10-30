# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3858 attackers** · **746,148 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 206 |
| Used a planted canary credential | 53 |
| Seen on more than one sensor | 274 |
| Stage-2 hosts named in payloads | 51 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4815 |
| `ssh-exploit` | 1324 |
| `ssh-bruteforce` | 1101 |
| `redis-exploit` | 668 |
| `mcp-abuse` | 264 |
| `litellm-key-replay` | 90 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 77 |
| `docker-abuse` | 50 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2513 |
| `redis` | 687 |
| `mcp` | 398 |
| `llamacpp` | 261 |
| `litellm` | 180 |
| `vllm` | 168 |
| `jupyter` | 166 |
| `docker` | 129 |
| `ollama` | 128 |
| `hfhub` | 124 |
| `php` | 62 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1565 |
| `345gs5662d34` | 1073 |
| `admin` | 735 |
| `ubuntu` | 360 |
| `user` | 183 |
| `ftpuser` | 178 |
| `test` | 140 |
| `guest` | 116 |
| `git` | 114 |
| `deploy` | 112 |
| `postgres` | 109 |
| `administrator` | 98 |
| `ftp` | 92 |
| `oracle` | 83 |
| `debian` | 76 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1071 |
| `3245gs5662d34` | 1063 |
| `123456` | 868 |
| `123` | 550 |
| `1234` | 404 |
| `12345678` | 321 |
| `admin` | 282 |
| `1` | 257 |
| `12345` | 255 |
| `P@ssw0rd` | 185 |
| `admin123` | 175 |
| `password` | 156 |
| `123456789` | 126 |
| `000000` | 125 |
| `!QAZ2wsx` | 109 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1442 |
| `cd` | 1249 |
| `cat` | 1248 |
| `echo` | 1236 |
| `crontab` | 1210 |
| `lscpu` | 1208 |
| `ls` | 1103 |
| `free` | 1101 |
| `df` | 1098 |
| `top` | 1098 |
| `w` | 1097 |
| `whoami` | 1097 |
| `INFO` | 453 |
| `canary_env` | 337 |
| `PING` | 321 |


_Generated from first-party honeypot capture. CC BY 4.0._
