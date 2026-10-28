# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3632 attackers** · **711,433 hostile actions** · covering 46 day(s) through 2026-10-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 196 |
| Used a planted canary credential | 43 |
| Seen on more than one sensor | 264 |
| Stage-2 hosts named in payloads | 46 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4199 |
| `ssh-exploit` | 1276 |
| `ssh-bruteforce` | 1016 |
| `redis-exploit` | 639 |
| `mcp-abuse` | 255 |
| `llamacpp-abuse` | 87 |
| `ollama-abuse` | 72 |
| `litellm-key-replay` | 63 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2377 |
| `redis` | 657 |
| `mcp` | 382 |
| `llamacpp` | 252 |
| `jupyter` | 162 |
| `vllm` | 159 |
| `litellm` | 148 |
| `docker` | 120 |
| `hfhub` | 119 |
| `ollama` | 118 |
| `php` | 59 |
| `ray` | 30 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1462 |
| `345gs5662d34` | 1031 |
| `admin` | 719 |
| `ubuntu` | 348 |
| `ftpuser` | 174 |
| `user` | 174 |
| `test` | 140 |
| `deploy` | 112 |
| `guest` | 111 |
| `git` | 111 |
| `postgres` | 106 |
| `administrator` | 96 |
| `ftp` | 87 |
| `oracle` | 79 |
| `AdminGPON` | 71 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1029 |
| `3245gs5662d34` | 1021 |
| `123456` | 842 |
| `123` | 520 |
| `1234` | 396 |
| `12345678` | 311 |
| `admin` | 275 |
| `1` | 249 |
| `12345` | 248 |
| `P@ssw0rd` | 182 |
| `admin123` | 167 |
| `password` | 152 |
| `123456789` | 125 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1395 |
| `cd` | 1204 |
| `cat` | 1203 |
| `echo` | 1190 |
| `crontab` | 1164 |
| `lscpu` | 1162 |
| `ls` | 1059 |
| `free` | 1057 |
| `df` | 1054 |
| `top` | 1054 |
| `w` | 1053 |
| `whoami` | 1053 |
| `INFO` | 433 |
| `canary_env` | 324 |
| `PING` | 306 |


_Generated from first-party honeypot capture. CC BY 4.0._
