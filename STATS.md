# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3081 attackers** · **612,685 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 186 |
| Used a planted canary credential | 35 |
| Seen on more than one sensor | 219 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2894 |
| `ssh-exploit` | 1198 |
| `ssh-bruteforce` | 698 |
| `redis-exploit` | 565 |
| `mcp-abuse` | 235 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 59 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 38 |
| `jupyter-abuse` | 33 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1972 |
| `redis` | 580 |
| `mcp` | 344 |
| `llamacpp` | 222 |
| `jupyter` | 136 |
| `vllm` | 131 |
| `litellm` | 124 |
| `hfhub` | 101 |
| `ollama` | 101 |
| `docker` | 92 |
| `ray` | 22 |
| `php` | 16 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1141 |
| `345gs5662d34` | 960 |
| `admin` | 662 |
| `ubuntu` | 313 |
| `user` | 161 |
| `ftpuser` | 158 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 98 |
| `administrator` | 93 |
| `oracle` | 74 |
| `ftp` | 72 |
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 958 |
| `3245gs5662d34` | 951 |
| `123456` | 774 |
| `123` | 507 |
| `1234` | 368 |
| `12345678` | 282 |
| `admin` | 242 |
| `12345` | 231 |
| `1` | 227 |
| `P@ssw0rd` | 167 |
| `password` | 157 |
| `admin123` | 149 |
| `000000` | 118 |
| `123456789` | 115 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1308 |
| `cd` | 1127 |
| `cat` | 1126 |
| `echo` | 1112 |
| `crontab` | 1090 |
| `lscpu` | 1088 |
| `ls` | 987 |
| `free` | 986 |
| `df` | 984 |
| `top` | 984 |
| `whoami` | 983 |
| `w` | 982 |
| `INFO` | 382 |
| `canary_env` | 292 |
| `PING` | 261 |


_Generated from first-party honeypot capture. CC BY 4.0._
