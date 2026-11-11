# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4601 attackers** · **1,049,773 hostile actions** · covering 60 day(s) through 2026-11-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 229 |
| Used a planted canary credential | 161 |
| Seen on more than one sensor | 361 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 8623 |
| `ssh-exploit` | 1390 |
| `ssh-bruteforce` | 1195 |
| `redis-exploit` | 903 |
| `mcp-abuse` | 295 |
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
| `ssh` | 2704 |
| `redis` | 932 |
| `mcp` | 494 |
| `llamacpp` | 371 |
| `litellm` | 291 |
| `vllm` | 250 |
| `jupyter` | 242 |
| `ollama` | 213 |
| `hfhub` | 183 |
| `docker` | 174 |
| `php` | 115 |
| `ray` | 41 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1650 |
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
| `uname` | 1508 |
| `cd` | 1299 |
| `cat` | 1298 |
| `echo` | 1271 |
| `crontab` | 1243 |
| `lscpu` | 1240 |
| `ls` | 1129 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 643 |
| `PING` | 488 |
| `canary_env` | 400 |


_Generated from first-party honeypot capture. CC BY 4.0._
