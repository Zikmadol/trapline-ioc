# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4922 attackers** · **1,121,484 hostile actions** · covering 62 day(s) through 2026-11-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 286 |
| Used a planted canary credential | 176 |
| Seen on more than one sensor | 428 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9694 |
| `ssh-exploit` | 1398 |
| `ssh-bruteforce` | 1338 |
| `redis-exploit` | 946 |
| `mcp-abuse` | 298 |
| `litellm-key-replay` | 164 |
| `docker-abuse` | 146 |
| `ollama-abuse` | 133 |
| `llamacpp-abuse` | 115 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2869 |
| `redis` | 976 |
| `mcp` | 509 |
| `llamacpp` | 395 |
| `litellm` | 307 |
| `vllm` | 303 |
| `docker` | 267 |
| `jupyter` | 255 |
| `ollama` | 236 |
| `hfhub` | 206 |
| `php` | 144 |
| `ray` | 46 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1691 |
| `345gs5662d34` | 1098 |
| `admin` | 847 |
| `ubuntu` | 411 |
| `ftpuser` | 208 |
| `user` | 195 |
| `test` | 158 |
| `guest` | 152 |
| `ftp` | 121 |
| `git` | 118 |
| `deploy` | 116 |
| `postgres` | 109 |
| `administrator` | 106 |
| `oracle` | 90 |
| `AdminGPON` | 89 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 947 |
| `123` | 600 |
| `1234` | 452 |
| `12345678` | 371 |
| `admin` | 349 |
| `12345` | 287 |
| `1` | 271 |
| `admin123` | 223 |
| `P@ssw0rd` | 218 |
| `password` | 167 |
| `123456789` | 138 |
| `000000` | 133 |
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
| `INFO` | 675 |
| `PING` | 512 |
| `canary_env` | 408 |


_Generated from first-party honeypot capture. CC BY 4.0._
