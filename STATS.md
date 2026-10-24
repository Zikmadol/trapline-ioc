# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3167 attackers** · **636,334 hostile actions** · covering 42 day(s) through 2026-10-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 37 |
| Seen on more than one sensor | 228 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3052 |
| `ssh-exploit` | 1213 |
| `ssh-bruteforce` | 742 |
| `redis-exploit` | 581 |
| `mcp-abuse` | 238 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 61 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 33 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2032 |
| `redis` | 596 |
| `mcp` | 347 |
| `llamacpp` | 227 |
| `jupyter` | 138 |
| `vllm` | 134 |
| `litellm` | 126 |
| `ollama` | 103 |
| `hfhub` | 101 |
| `docker` | 96 |
| `php` | 28 |
| `ray` | 22 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1187 |
| `345gs5662d34` | 971 |
| `admin` | 671 |
| `ubuntu` | 315 |
| `ftpuser` | 162 |
| `user` | 162 |
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
| `345gs5662d34` | 969 |
| `3245gs5662d34` | 962 |
| `123456` | 782 |
| `123` | 508 |
| `1234` | 371 |
| `12345678` | 287 |
| `admin` | 248 |
| `1` | 232 |
| `12345` | 232 |
| `P@ssw0rd` | 170 |
| `password` | 156 |
| `admin123` | 154 |
| `000000` | 119 |
| `123456789` | 116 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1321 |
| `cd` | 1139 |
| `cat` | 1138 |
| `echo` | 1123 |
| `crontab` | 1101 |
| `lscpu` | 1099 |
| `ls` | 998 |
| `free` | 997 |
| `df` | 995 |
| `top` | 995 |
| `whoami` | 994 |
| `w` | 993 |
| `INFO` | 391 |
| `canary_env` | 296 |
| `PING` | 267 |


_Generated from first-party honeypot capture. CC BY 4.0._
