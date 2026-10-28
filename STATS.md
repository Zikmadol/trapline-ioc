# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3613 attackers** · **707,688 hostile actions** · covering 46 day(s) through 2026-10-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 195 |
| Used a planted canary credential | 43 |
| Seen on more than one sensor | 263 |
| Stage-2 hosts named in payloads | 45 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4093 |
| `ssh-exploit` | 1271 |
| `ssh-bruteforce` | 1008 |
| `redis-exploit` | 637 |
| `mcp-abuse` | 254 |
| `llamacpp-abuse` | 85 |
| `ollama-abuse` | 71 |
| `litellm-key-replay` | 63 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2364 |
| `redis` | 655 |
| `mcp` | 379 |
| `llamacpp` | 250 |
| `jupyter` | 160 |
| `vllm` | 156 |
| `litellm` | 145 |
| `docker` | 118 |
| `ollama` | 116 |
| `hfhub` | 115 |
| `php` | 59 |
| `ray` | 29 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1452 |
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
| `INFO` | 431 |
| `canary_env` | 321 |
| `PING` | 304 |


_Generated from first-party honeypot capture. CC BY 4.0._
