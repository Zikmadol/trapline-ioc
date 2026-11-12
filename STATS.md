# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4752 attackers** · **1,101,557 hostile actions** · covering 61 day(s) through 2026-11-12

| signal | count |
|---|---|
| GPU / AI-hardware probing | 249 |
| Used a planted canary credential | 175 |
| Seen on more than one sensor | 392 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9397 |
| `ssh-exploit` | 1395 |
| `ssh-bruteforce` | 1246 |
| `redis-exploit` | 932 |
| `mcp-abuse` | 297 |
| `litellm-key-replay` | 165 |
| `ollama-abuse` | 128 |
| `llamacpp-abuse` | 116 |
| `docker-abuse` | 96 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 22 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2769 |
| `redis` | 962 |
| `mcp` | 504 |
| `llamacpp` | 386 |
| `litellm` | 300 |
| `vllm` | 274 |
| `jupyter` | 247 |
| `ollama` | 226 |
| `docker` | 208 |
| `hfhub` | 194 |
| `php` | 129 |
| `ray` | 44 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1675 |
| `345gs5662d34` | 1098 |
| `admin` | 829 |
| `ubuntu` | 411 |
| `ftpuser` | 207 |
| `user` | 194 |
| `test` | 154 |
| `guest` | 151 |
| `ftp` | 119 |
| `git` | 117 |
| `deploy` | 114 |
| `postgres` | 109 |
| `administrator` | 106 |
| `oracle` | 90 |
| `AdminGPON` | 88 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 941 |
| `123` | 598 |
| `1234` | 444 |
| `12345678` | 368 |
| `admin` | 342 |
| `12345` | 283 |
| `1` | 271 |
| `admin123` | 218 |
| `P@ssw0rd` | 216 |
| `password` | 161 |
| `123456789` | 136 |
| `000000` | 133 |
| `!QAZ2wsx` | 123 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1513 |
| `cat` | 1299 |
| `cd` | 1299 |
| `echo` | 1275 |
| `crontab` | 1245 |
| `lscpu` | 1242 |
| `ls` | 1130 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 664 |
| `PING` | 508 |
| `canary_env` | 405 |


_Generated from first-party honeypot capture. CC BY 4.0._
