# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3656 attackers** · **720,796 hostile actions** · covering 46 day(s) through 2026-10-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 196 |
| Used a planted canary credential | 43 |
| Seen on more than one sensor | 265 |
| Stage-2 hosts named in payloads | 47 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4305 |
| `ssh-exploit` | 1284 |
| `ssh-bruteforce` | 1026 |
| `redis-exploit` | 643 |
| `mcp-abuse` | 256 |
| `llamacpp-abuse` | 85 |
| `ollama-abuse` | 73 |
| `litellm-key-replay` | 63 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2395 |
| `redis` | 660 |
| `mcp` | 385 |
| `llamacpp` | 252 |
| `jupyter` | 162 |
| `vllm` | 160 |
| `litellm` | 148 |
| `ollama` | 121 |
| `docker` | 121 |
| `hfhub` | 119 |
| `php` | 59 |
| `ray` | 30 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1472 |
| `345gs5662d34` | 1039 |
| `admin` | 720 |
| `ubuntu` | 348 |
| `ftpuser` | 175 |
| `user` | 174 |
| `test` | 140 |
| `guest` | 112 |
| `deploy` | 112 |
| `git` | 111 |
| `postgres` | 106 |
| `administrator` | 96 |
| `ftp` | 88 |
| `oracle` | 79 |
| `dev` | 72 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1037 |
| `3245gs5662d34` | 1029 |
| `123456` | 851 |
| `123` | 520 |
| `1234` | 396 |
| `12345678` | 312 |
| `admin` | 275 |
| `1` | 250 |
| `12345` | 250 |
| `P@ssw0rd` | 182 |
| `admin123` | 169 |
| `password` | 152 |
| `123456789` | 125 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1404 |
| `cd` | 1213 |
| `cat` | 1212 |
| `echo` | 1199 |
| `crontab` | 1173 |
| `lscpu` | 1171 |
| `ls` | 1068 |
| `free` | 1066 |
| `df` | 1063 |
| `top` | 1063 |
| `w` | 1062 |
| `whoami` | 1062 |
| `INFO` | 437 |
| `canary_env` | 325 |
| `PING` | 309 |


_Generated from first-party honeypot capture. CC BY 4.0._
