# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3635 attackers** · **719,905 hostile actions** · covering 46 day(s) through 2026-10-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 196 |
| Used a planted canary credential | 43 |
| Seen on more than one sensor | 265 |
| Stage-2 hosts named in payloads | 46 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4253 |
| `ssh-exploit` | 1278 |
| `ssh-bruteforce` | 1015 |
| `redis-exploit` | 640 |
| `mcp-abuse` | 255 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 73 |
| `litellm-key-replay` | 63 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 36 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2378 |
| `redis` | 658 |
| `mcp` | 383 |
| `llamacpp` | 252 |
| `jupyter` | 162 |
| `vllm` | 159 |
| `litellm` | 148 |
| `ollama` | 121 |
| `docker` | 121 |
| `hfhub` | 119 |
| `php` | 59 |
| `ray` | 30 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1462 |
| `345gs5662d34` | 1032 |
| `admin` | 719 |
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
| `oracle` | 78 |
| `AdminGPON` | 71 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1030 |
| `3245gs5662d34` | 1022 |
| `123456` | 844 |
| `123` | 520 |
| `1234` | 396 |
| `12345678` | 312 |
| `admin` | 275 |
| `1` | 249 |
| `12345` | 249 |
| `P@ssw0rd` | 182 |
| `admin123` | 168 |
| `password` | 152 |
| `123456789` | 125 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1396 |
| `cd` | 1205 |
| `cat` | 1204 |
| `echo` | 1191 |
| `crontab` | 1165 |
| `lscpu` | 1163 |
| `ls` | 1060 |
| `free` | 1058 |
| `df` | 1055 |
| `top` | 1055 |
| `w` | 1054 |
| `whoami` | 1054 |
| `INFO` | 434 |
| `canary_env` | 324 |
| `PING` | 307 |


_Generated from first-party honeypot capture. CC BY 4.0._
