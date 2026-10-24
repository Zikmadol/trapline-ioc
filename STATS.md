# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3173 attackers** · **636,748 hostile actions** · covering 42 day(s) through 2026-10-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 37 |
| Seen on more than one sensor | 229 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3065 |
| `ssh-exploit` | 1214 |
| `ssh-bruteforce` | 744 |
| `redis-exploit` | 581 |
| `mcp-abuse` | 239 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 62 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2035 |
| `redis` | 596 |
| `mcp` | 349 |
| `llamacpp` | 228 |
| `jupyter` | 139 |
| `vllm` | 135 |
| `litellm` | 126 |
| `ollama` | 104 |
| `hfhub` | 102 |
| `docker` | 96 |
| `php` | 29 |
| `ray` | 22 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1190 |
| `345gs5662d34` | 972 |
| `admin` | 672 |
| `ubuntu` | 317 |
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
| `345gs5662d34` | 970 |
| `3245gs5662d34` | 963 |
| `123456` | 782 |
| `123` | 508 |
| `1234` | 371 |
| `12345678` | 287 |
| `admin` | 248 |
| `1` | 232 |
| `12345` | 232 |
| `P@ssw0rd` | 169 |
| `password` | 157 |
| `admin123` | 154 |
| `000000` | 119 |
| `123456789` | 116 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1322 |
| `cd` | 1140 |
| `cat` | 1139 |
| `echo` | 1124 |
| `crontab` | 1102 |
| `lscpu` | 1100 |
| `ls` | 999 |
| `free` | 998 |
| `df` | 996 |
| `top` | 996 |
| `whoami` | 995 |
| `w` | 994 |
| `INFO` | 391 |
| `canary_env` | 298 |
| `PING` | 267 |


_Generated from first-party honeypot capture. CC BY 4.0._
