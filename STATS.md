# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3176 attackers** · **641,772 hostile actions** · covering 42 day(s) through 2026-10-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 37 |
| Seen on more than one sensor | 229 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3080 |
| `ssh-exploit` | 1215 |
| `ssh-bruteforce` | 746 |
| `redis-exploit` | 581 |
| `mcp-abuse` | 239 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 62 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2038 |
| `redis` | 596 |
| `mcp` | 349 |
| `llamacpp` | 228 |
| `jupyter` | 140 |
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
| `root` | 1192 |
| `345gs5662d34` | 973 |
| `admin` | 672 |
| `ubuntu` | 317 |
| `ftpuser` | 162 |
| `user` | 162 |
| `test` | 132 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 100 |
| `administrator` | 93 |
| `ftp` | 75 |
| `oracle` | 75 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 971 |
| `3245gs5662d34` | 964 |
| `123456` | 783 |
| `123` | 509 |
| `1234` | 372 |
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
| `uname` | 1323 |
| `cd` | 1141 |
| `cat` | 1140 |
| `echo` | 1125 |
| `crontab` | 1103 |
| `lscpu` | 1101 |
| `ls` | 1000 |
| `free` | 999 |
| `df` | 997 |
| `top` | 997 |
| `whoami` | 996 |
| `w` | 995 |
| `INFO` | 391 |
| `canary_env` | 298 |
| `PING` | 267 |


_Generated from first-party honeypot capture. CC BY 4.0._
