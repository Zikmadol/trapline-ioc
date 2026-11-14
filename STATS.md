# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4997 attackers** · **1,143,021 hostile actions** · covering 63 day(s) through 2026-11-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 292 |
| Used a planted canary credential | 178 |
| Seen on more than one sensor | 433 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9873 |
| `ssh-exploit` | 1400 |
| `ssh-bruteforce` | 1386 |
| `redis-exploit` | 954 |
| `mcp-abuse` | 303 |
| `litellm-key-replay` | 164 |
| `docker-abuse` | 151 |
| `ollama-abuse` | 136 |
| `llamacpp-abuse` | 118 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2920 |
| `redis` | 985 |
| `mcp` | 517 |
| `llamacpp` | 401 |
| `litellm` | 309 |
| `vllm` | 306 |
| `docker` | 274 |
| `jupyter` | 258 |
| `ollama` | 239 |
| `hfhub` | 209 |
| `php` | 145 |
| `ray` | 46 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1701 |
| `345gs5662d34` | 1098 |
| `admin` | 860 |
| `ubuntu` | 414 |
| `ftpuser` | 209 |
| `user` | 197 |
| `test` | 164 |
| `guest` | 159 |
| `ftp` | 122 |
| `git` | 118 |
| `deploy` | 116 |
| `postgres` | 109 |
| `administrator` | 106 |
| `oracle` | 91 |
| `AdminGPON` | 90 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 950 |
| `123` | 601 |
| `1234` | 456 |
| `12345678` | 375 |
| `admin` | 352 |
| `12345` | 290 |
| `1` | 272 |
| `admin123` | 225 |
| `P@ssw0rd` | 220 |
| `password` | 167 |
| `123456789` | 139 |
| `000000` | 133 |
| `!QAZ2wsx` | 125 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1514 |
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
| `INFO` | 681 |
| `PING` | 520 |
| `canary_env` | 417 |


_Generated from first-party honeypot capture. CC BY 4.0._
