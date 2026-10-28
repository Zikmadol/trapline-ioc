# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3617 attackers** · **708,244 hostile actions** · covering 46 day(s) through 2026-10-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 195 |
| Used a planted canary credential | 43 |
| Seen on more than one sensor | 264 |
| Stage-2 hosts named in payloads | 46 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4137 |
| `ssh-exploit` | 1270 |
| `ssh-bruteforce` | 1010 |
| `redis-exploit` | 638 |
| `mcp-abuse` | 254 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 71 |
| `litellm-key-replay` | 64 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2365 |
| `redis` | 656 |
| `mcp` | 381 |
| `llamacpp` | 251 |
| `jupyter` | 162 |
| `vllm` | 156 |
| `litellm` | 148 |
| `docker` | 120 |
| `hfhub` | 118 |
| `ollama` | 116 |
| `php` | 59 |
| `ray` | 29 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1453 |
| `345gs5662d34` | 1025 |
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
| `345gs5662d34` | 1023 |
| `3245gs5662d34` | 1015 |
| `123456` | 835 |
| `123` | 520 |
| `1234` | 396 |
| `12345678` | 311 |
| `admin` | 275 |
| `1` | 249 |
| `12345` | 248 |
| `P@ssw0rd` | 182 |
| `admin123` | 167 |
| `password` | 152 |
| `123456789` | 124 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1388 |
| `cd` | 1198 |
| `cat` | 1197 |
| `echo` | 1184 |
| `crontab` | 1158 |
| `lscpu` | 1156 |
| `ls` | 1053 |
| `free` | 1051 |
| `df` | 1048 |
| `top` | 1048 |
| `w` | 1047 |
| `whoami` | 1047 |
| `INFO` | 432 |
| `canary_env` | 322 |
| `PING` | 305 |


_Generated from first-party honeypot capture. CC BY 4.0._
