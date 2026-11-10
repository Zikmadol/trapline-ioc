# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4594 attackers** · **1,049,196 hostile actions** · covering 59 day(s) through 2026-11-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 229 |
| Used a planted canary credential | 160 |
| Seen on more than one sensor | 359 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 8558 |
| `ssh-exploit` | 1389 |
| `ssh-bruteforce` | 1195 |
| `redis-exploit` | 899 |
| `mcp-abuse` | 294 |
| `litellm-key-replay` | 162 |
| `ollama-abuse` | 122 |
| `llamacpp-abuse` | 111 |
| `docker-abuse` | 67 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 22 |
| `php-abuse` | 20 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2702 |
| `redis` | 928 |
| `mcp` | 492 |
| `llamacpp` | 370 |
| `litellm` | 291 |
| `vllm` | 249 |
| `jupyter` | 242 |
| `ollama` | 213 |
| `hfhub` | 182 |
| `docker` | 174 |
| `php` | 114 |
| `ray` | 41 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1649 |
| `345gs5662d34` | 1098 |
| `admin` | 814 |
| `ubuntu` | 408 |
| `ftpuser` | 202 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 144 |
| `git` | 117 |
| `ftp` | 115 |
| `deploy` | 113 |
| `postgres` | 109 |
| `administrator` | 105 |
| `oracle` | 90 |
| `AdminGPON` | 86 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 933 |
| `123` | 597 |
| `1234` | 438 |
| `12345678` | 362 |
| `admin` | 335 |
| `12345` | 277 |
| `1` | 269 |
| `admin123` | 211 |
| `P@ssw0rd` | 211 |
| `password` | 161 |
| `123456789` | 134 |
| `000000` | 134 |
| `!QAZ2wsx` | 120 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1507 |
| `cd` | 1299 |
| `cat` | 1297 |
| `echo` | 1270 |
| `crontab` | 1243 |
| `lscpu` | 1240 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 640 |
| `PING` | 485 |
| `canary_env` | 399 |


_Generated from first-party honeypot capture. CC BY 4.0._
