# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5372 attackers** · **1,190,406 hostile actions** · covering 65 day(s) through 2026-11-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 300 |
| Used a planted canary credential | 198 |
| Seen on more than one sensor | 450 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10950 |
| `ssh-bruteforce` | 1647 |
| `ssh-exploit` | 1406 |
| `redis-exploit` | 988 |
| `mcp-abuse` | 306 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 163 |
| `ollama-abuse` | 148 |
| `llamacpp-abuse` | 127 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 25 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3196 |
| `redis` | 1020 |
| `mcp` | 528 |
| `llamacpp` | 426 |
| `litellm` | 333 |
| `vllm` | 326 |
| `docker` | 291 |
| `jupyter` | 276 |
| `ollama` | 262 |
| `hfhub` | 218 |
| `php` | 156 |
| `ray` | 48 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1760 |
| `345gs5662d34` | 1098 |
| `admin` | 894 |
| `ubuntu` | 415 |
| `ftpuser` | 215 |
| `user` | 212 |
| `guest` | 206 |
| `test` | 171 |
| `ftp` | 129 |
| `git` | 119 |
| `deploy` | 116 |
| `postgres` | 111 |
| `administrator` | 106 |
| `config` | 104 |
| `support` | 100 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 966 |
| `123` | 608 |
| `1234` | 468 |
| `12345678` | 385 |
| `admin` | 370 |
| `12345` | 298 |
| `1` | 278 |
| `admin123` | 233 |
| `P@ssw0rd` | 229 |
| `password` | 174 |
| `123456789` | 144 |
| `000000` | 136 |
| `1111` | 128 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1520 |
| `cat` | 1306 |
| `cd` | 1302 |
| `echo` | 1279 |
| `crontab` | 1248 |
| `lscpu` | 1245 |
| `ls` | 1134 |
| `whoami` | 1131 |
| `free` | 1129 |
| `df` | 1127 |
| `top` | 1126 |
| `w` | 1125 |
| `INFO` | 705 |
| `PING` | 539 |
| `canary_env` | 431 |


_Generated from first-party honeypot capture. CC BY 4.0._
