# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5984 attackers** · **1,328,600 hostile actions** · covering 72 day(s) through 2026-11-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 329 |
| Used a planted canary credential | 250 |
| Seen on more than one sensor | 500 |
| Stage-2 hosts named in payloads | 69 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13525 |
| `ssh-bruteforce` | 1908 |
| `ssh-exploit` | 1462 |
| `redis-exploit` | 1080 |
| `mcp-abuse` | 334 |
| `docker-abuse` | 211 |
| `litellm-key-replay` | 188 |
| `ollama-abuse` | 162 |
| `llamacpp-abuse` | 143 |
| `jupyter-abuse` | 51 |
| `litellm-abuse` | 31 |
| `vllm-abuse` | 29 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3526 |
| `redis` | 1112 |
| `mcp` | 596 |
| `llamacpp` | 507 |
| `vllm` | 384 |
| `litellm` | 382 |
| `docker` | 354 |
| `jupyter` | 306 |
| `ollama` | 291 |
| `hfhub` | 250 |
| `php` | 184 |
| `ray` | 59 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1910 |
| `345gs5662d34` | 1106 |
| `admin` | 940 |
| `ubuntu` | 435 |
| `guest` | 235 |
| `ftpuser` | 228 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 143 |
| `deploy` | 129 |
| `config` | 128 |
| `git` | 125 |
| `administrator` | 116 |
| `support` | 114 |
| `postgres` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1031 |
| `123` | 631 |
| `1234` | 516 |
| `12345678` | 405 |
| `admin` | 404 |
| `12345` | 348 |
| `1` | 299 |
| `admin123` | 253 |
| `P@ssw0rd` | 250 |
| `password` | 172 |
| `123456789` | 150 |
| `1111` | 147 |
| `000000` | 144 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1595 |
| `cat` | 1370 |
| `cd` | 1365 |
| `echo` | 1339 |
| `crontab` | 1306 |
| `lscpu` | 1299 |
| `ls` | 1189 |
| `free` | 1183 |
| `whoami` | 1183 |
| `df` | 1180 |
| `top` | 1179 |
| `w` | 1179 |
| `INFO` | 764 |
| `PING` | 591 |
| `canary_env` | 486 |


_Generated from first-party honeypot capture. CC BY 4.0._
