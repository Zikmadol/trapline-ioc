# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3481 attackers** · **689,625 hostile actions** · covering 45 day(s) through 2026-10-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 194 |
| Used a planted canary credential | 40 |
| Seen on more than one sensor | 256 |
| Stage-2 hosts named in payloads | 45 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3591 |
| `ssh-exploit` | 1249 |
| `ssh-bruteforce` | 931 |
| `redis-exploit` | 623 |
| `mcp-abuse` | 249 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 70 |
| `litellm-key-replay` | 61 |
| `docker-abuse` | 45 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2261 |
| `redis` | 639 |
| `mcp` | 370 |
| `llamacpp` | 240 |
| `jupyter` | 155 |
| `vllm` | 149 |
| `litellm` | 140 |
| `ollama` | 115 |
| `docker` | 111 |
| `hfhub` | 110 |
| `php` | 50 |
| `ray` | 27 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1392 |
| `345gs5662d34` | 1004 |
| `admin` | 700 |
| `ubuntu` | 336 |
| `ftpuser` | 169 |
| `user` | 169 |
| `test` | 138 |
| `deploy` | 112 |
| `git` | 111 |
| `guest` | 109 |
| `postgres` | 103 |
| `administrator` | 96 |
| `ftp` | 82 |
| `oracle` | 76 |
| `AdminGPON` | 70 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1002 |
| `3245gs5662d34` | 994 |
| `123456` | 819 |
| `123` | 514 |
| `1234` | 388 |
| `12345678` | 305 |
| `admin` | 269 |
| `12345` | 243 |
| `1` | 242 |
| `P@ssw0rd` | 179 |
| `admin123` | 164 |
| `password` | 152 |
| `000000` | 123 |
| `123456789` | 122 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1366 |
| `cd` | 1175 |
| `cat` | 1174 |
| `echo` | 1160 |
| `crontab` | 1136 |
| `lscpu` | 1134 |
| `ls` | 1030 |
| `free` | 1029 |
| `df` | 1027 |
| `top` | 1027 |
| `whoami` | 1026 |
| `w` | 1025 |
| `INFO` | 419 |
| `canary_env` | 314 |
| `PING` | 293 |


_Generated from first-party honeypot capture. CC BY 4.0._
