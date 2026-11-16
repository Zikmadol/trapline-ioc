# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5392 attackers** · **1,192,138 hostile actions** · covering 65 day(s) through 2026-11-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 300 |
| Used a planted canary credential | 198 |
| Seen on more than one sensor | 452 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10978 |
| `ssh-bruteforce` | 1665 |
| `ssh-exploit` | 1407 |
| `redis-exploit` | 989 |
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
| `ssh` | 3216 |
| `redis` | 1021 |
| `mcp` | 530 |
| `llamacpp` | 427 |
| `litellm` | 334 |
| `vllm` | 326 |
| `docker` | 291 |
| `jupyter` | 276 |
| `ollama` | 262 |
| `hfhub` | 220 |
| `php` | 156 |
| `ray` | 48 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1766 |
| `345gs5662d34` | 1099 |
| `admin` | 894 |
| `ubuntu` | 418 |
| `ftpuser` | 215 |
| `user` | 213 |
| `guest` | 207 |
| `test` | 171 |
| `ftp` | 129 |
| `git` | 120 |
| `deploy` | 117 |
| `postgres` | 111 |
| `config` | 108 |
| `administrator` | 106 |
| `support` | 103 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1097 |
| `3245gs5662d34` | 1089 |
| `123456` | 969 |
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
| `uname` | 1523 |
| `cat` | 1308 |
| `cd` | 1304 |
| `echo` | 1281 |
| `crontab` | 1250 |
| `lscpu` | 1247 |
| `ls` | 1136 |
| `whoami` | 1133 |
| `free` | 1131 |
| `df` | 1129 |
| `top` | 1128 |
| `w` | 1127 |
| `INFO` | 706 |
| `PING` | 539 |
| `canary_env` | 431 |


_Generated from first-party honeypot capture. CC BY 4.0._
