# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4361 attackers** · **910,295 hostile actions** · covering 56 day(s) through 2026-11-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 220 |
| Used a planted canary credential | 148 |
| Seen on more than one sensor | 327 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6938 |
| `ssh-exploit` | 1375 |
| `ssh-bruteforce` | 1171 |
| `redis-exploit` | 777 |
| `mcp-abuse` | 282 |
| `litellm-key-replay` | 149 |
| `ollama-abuse` | 109 |
| `llamacpp-abuse` | 102 |
| `docker-abuse` | 59 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 17 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2649 |
| `redis` | 803 |
| `mcp` | 462 |
| `llamacpp` | 337 |
| `litellm` | 269 |
| `jupyter` | 222 |
| `vllm` | 215 |
| `ollama` | 185 |
| `hfhub` | 166 |
| `docker` | 159 |
| `php` | 96 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1632 |
| `345gs5662d34` | 1098 |
| `admin` | 794 |
| `ubuntu` | 402 |
| `user` | 194 |
| `ftpuser` | 193 |
| `test` | 150 |
| `guest` | 135 |
| `git` | 117 |
| `deploy` | 113 |
| `postgres` | 108 |
| `ftp` | 106 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 81 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 918 |
| `123` | 593 |
| `1234` | 424 |
| `12345678` | 348 |
| `admin` | 318 |
| `12345` | 269 |
| `1` | 268 |
| `P@ssw0rd` | 202 |
| `admin123` | 198 |
| `password` | 160 |
| `123456789` | 134 |
| `000000` | 131 |
| `!QAZ2wsx` | 114 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1494 |
| `cd` | 1291 |
| `cat` | 1289 |
| `echo` | 1268 |
| `crontab` | 1241 |
| `lscpu` | 1238 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 537 |
| `PING` | 390 |
| `canary_env` | 382 |


_Generated from first-party honeypot capture. CC BY 4.0._
