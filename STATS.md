# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4894 attackers** · **1,118,640 hostile actions** · covering 62 day(s) through 2026-11-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 281 |
| Used a planted canary credential | 176 |
| Seen on more than one sensor | 421 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9628 |
| `ssh-exploit` | 1398 |
| `ssh-bruteforce` | 1320 |
| `redis-exploit` | 943 |
| `mcp-abuse` | 298 |
| `litellm-key-replay` | 164 |
| `docker-abuse` | 141 |
| `ollama-abuse` | 132 |
| `llamacpp-abuse` | 115 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 22 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2850 |
| `redis` | 973 |
| `mcp` | 507 |
| `llamacpp` | 390 |
| `litellm` | 305 |
| `vllm` | 298 |
| `docker` | 262 |
| `jupyter` | 254 |
| `ollama` | 232 |
| `hfhub` | 199 |
| `php` | 141 |
| `ray` | 46 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1690 |
| `345gs5662d34` | 1098 |
| `admin` | 841 |
| `ubuntu` | 411 |
| `ftpuser` | 208 |
| `user` | 194 |
| `test` | 158 |
| `guest` | 152 |
| `ftp` | 121 |
| `git` | 118 |
| `deploy` | 115 |
| `postgres` | 109 |
| `administrator` | 106 |
| `oracle` | 91 |
| `AdminGPON` | 89 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 947 |
| `123` | 600 |
| `1234` | 450 |
| `12345678` | 371 |
| `admin` | 349 |
| `12345` | 287 |
| `1` | 271 |
| `admin123` | 223 |
| `P@ssw0rd` | 218 |
| `password` | 167 |
| `123456789` | 138 |
| `000000` | 132 |
| `!QAZ2wsx` | 124 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1513 |
| `cat` | 1302 |
| `cd` | 1299 |
| `echo` | 1276 |
| `crontab` | 1245 |
| `lscpu` | 1242 |
| `ls` | 1131 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1124 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 674 |
| `PING` | 511 |
| `canary_env` | 408 |


_Generated from first-party honeypot capture. CC BY 4.0._
