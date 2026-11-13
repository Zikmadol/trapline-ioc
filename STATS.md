# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4783 attackers** · **1,108,941 hostile actions** · covering 62 day(s) through 2026-11-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 258 |
| Used a planted canary credential | 175 |
| Seen on more than one sensor | 397 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9445 |
| `ssh-exploit` | 1396 |
| `ssh-bruteforce` | 1263 |
| `redis-exploit` | 934 |
| `mcp-abuse` | 298 |
| `litellm-key-replay` | 165 |
| `ollama-abuse` | 128 |
| `llamacpp-abuse` | 115 |
| `docker-abuse` | 106 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 24 |
| `php-abuse` | 22 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2786 |
| `redis` | 964 |
| `mcp` | 505 |
| `llamacpp` | 386 |
| `litellm` | 300 |
| `vllm` | 279 |
| `jupyter` | 250 |
| `ollama` | 226 |
| `docker` | 221 |
| `hfhub` | 194 |
| `php` | 130 |
| `ray` | 44 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1678 |
| `345gs5662d34` | 1098 |
| `admin` | 830 |
| `ubuntu` | 412 |
| `ftpuser` | 207 |
| `user` | 194 |
| `test` | 156 |
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
| `123456` | 943 |
| `123` | 599 |
| `1234` | 445 |
| `12345678` | 369 |
| `admin` | 343 |
| `12345` | 284 |
| `1` | 271 |
| `admin123` | 219 |
| `P@ssw0rd` | 217 |
| `password` | 162 |
| `123456789` | 137 |
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
| `INFO` | 667 |
| `PING` | 507 |
| `canary_env` | 406 |


_Generated from first-party honeypot capture. CC BY 4.0._
