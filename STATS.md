# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4844 attackers** · **1,114,180 hostile actions** · covering 62 day(s) through 2026-11-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 280 |
| Used a planted canary credential | 175 |
| Seen on more than one sensor | 414 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9525 |
| `ssh-exploit` | 1397 |
| `ssh-bruteforce` | 1286 |
| `redis-exploit` | 938 |
| `mcp-abuse` | 298 |
| `litellm-key-replay` | 163 |
| `docker-abuse` | 137 |
| `ollama-abuse` | 130 |
| `llamacpp-abuse` | 115 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 22 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2811 |
| `redis` | 968 |
| `mcp` | 505 |
| `llamacpp` | 387 |
| `litellm` | 302 |
| `vllm` | 293 |
| `docker` | 255 |
| `jupyter` | 252 |
| `ollama` | 228 |
| `hfhub` | 196 |
| `php` | 131 |
| `ray` | 45 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1683 |
| `345gs5662d34` | 1098 |
| `admin` | 834 |
| `ubuntu` | 412 |
| `ftpuser` | 207 |
| `user` | 194 |
| `test` | 158 |
| `guest` | 151 |
| `ftp` | 119 |
| `git` | 117 |
| `deploy` | 115 |
| `postgres` | 109 |
| `administrator` | 106 |
| `oracle` | 90 |
| `AdminGPON` | 88 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 944 |
| `123` | 600 |
| `1234` | 447 |
| `12345678` | 370 |
| `admin` | 345 |
| `12345` | 287 |
| `1` | 271 |
| `admin123` | 219 |
| `P@ssw0rd` | 217 |
| `password` | 164 |
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
