# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4942 attackers** · **1,121,866 hostile actions** · covering 62 day(s) through 2026-11-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 287 |
| Used a planted canary credential | 178 |
| Seen on more than one sensor | 431 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9730 |
| `ssh-exploit` | 1399 |
| `ssh-bruteforce` | 1347 |
| `redis-exploit` | 948 |
| `mcp-abuse` | 300 |
| `litellm-key-replay` | 164 |
| `docker-abuse` | 146 |
| `ollama-abuse` | 135 |
| `llamacpp-abuse` | 119 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2879 |
| `redis` | 979 |
| `mcp` | 511 |
| `llamacpp` | 399 |
| `litellm` | 307 |
| `vllm` | 304 |
| `docker` | 270 |
| `jupyter` | 256 |
| `ollama` | 238 |
| `hfhub` | 206 |
| `php` | 144 |
| `ray` | 46 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1696 |
| `345gs5662d34` | 1098 |
| `admin` | 850 |
| `ubuntu` | 411 |
| `ftpuser` | 209 |
| `user` | 195 |
| `test` | 160 |
| `guest` | 154 |
| `ftp` | 122 |
| `git` | 118 |
| `deploy` | 116 |
| `postgres` | 109 |
| `administrator` | 106 |
| `oracle` | 91 |
| `config` | 90 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 949 |
| `123` | 601 |
| `1234` | 454 |
| `12345678` | 373 |
| `admin` | 351 |
| `12345` | 289 |
| `1` | 271 |
| `admin123` | 225 |
| `P@ssw0rd` | 220 |
| `password` | 167 |
| `123456789` | 139 |
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
| `INFO` | 677 |
| `PING` | 515 |
| `canary_env` | 414 |


_Generated from first-party honeypot capture. CC BY 4.0._
