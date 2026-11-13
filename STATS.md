# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4855 attackers** · **1,114,564 hostile actions** · covering 62 day(s) through 2026-11-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 280 |
| Used a planted canary credential | 176 |
| Seen on more than one sensor | 416 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9556 |
| `ssh-exploit` | 1397 |
| `ssh-bruteforce` | 1293 |
| `redis-exploit` | 938 |
| `mcp-abuse` | 298 |
| `litellm-key-replay` | 164 |
| `docker-abuse` | 139 |
| `ollama-abuse` | 131 |
| `llamacpp-abuse` | 115 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 22 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2818 |
| `redis` | 968 |
| `mcp` | 505 |
| `llamacpp` | 388 |
| `litellm` | 303 |
| `vllm` | 297 |
| `docker` | 257 |
| `jupyter` | 252 |
| `ollama` | 229 |
| `hfhub` | 197 |
| `php` | 131 |
| `ray` | 45 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1683 |
| `345gs5662d34` | 1098 |
| `admin` | 836 |
| `ubuntu` | 411 |
| `ftpuser` | 208 |
| `user` | 194 |
| `test` | 159 |
| `guest` | 152 |
| `ftp` | 121 |
| `git` | 117 |
| `deploy` | 115 |
| `postgres` | 110 |
| `administrator` | 106 |
| `oracle` | 90 |
| `config` | 89 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 946 |
| `123` | 600 |
| `1234` | 450 |
| `12345678` | 371 |
| `admin` | 347 |
| `12345` | 288 |
| `1` | 271 |
| `admin123` | 221 |
| `P@ssw0rd` | 218 |
| `password` | 165 |
| `123456789` | 138 |
| `000000` | 132 |
| `!QAZ2wsx` | 123 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1513 |
| `cat` | 1300 |
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
| `INFO` | 671 |
| `PING` | 509 |
| `canary_env` | 407 |


_Generated from first-party honeypot capture. CC BY 4.0._
