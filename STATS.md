# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5725 attackers** · **1,227,146 hostile actions** · covering 68 day(s) through 2026-11-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 314 |
| Used a planted canary credential | 238 |
| Seen on more than one sensor | 476 |
| Stage-2 hosts named in payloads | 65 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 12553 |
| `ssh-bruteforce` | 1839 |
| `ssh-exploit` | 1441 |
| `redis-exploit` | 1018 |
| `mcp-abuse` | 320 |
| `docker-abuse` | 183 |
| `litellm-key-replay` | 182 |
| `ollama-abuse` | 154 |
| `llamacpp-abuse` | 134 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3429 |
| `redis` | 1050 |
| `mcp` | 554 |
| `llamacpp` | 456 |
| `litellm` | 349 |
| `vllm` | 346 |
| `docker` | 316 |
| `jupyter` | 284 |
| `ollama` | 277 |
| `hfhub` | 232 |
| `php` | 165 |
| `ray` | 53 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1863 |
| `345gs5662d34` | 1103 |
| `admin` | 915 |
| `ubuntu` | 424 |
| `guest` | 226 |
| `ftpuser` | 221 |
| `user` | 218 |
| `test` | 174 |
| `ftp` | 135 |
| `deploy` | 124 |
| `git` | 123 |
| `config` | 120 |
| `support` | 113 |
| `postgres` | 112 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1100 |
| `3245gs5662d34` | 1092 |
| `123456` | 1004 |
| `123` | 614 |
| `1234` | 496 |
| `12345678` | 393 |
| `admin` | 388 |
| `12345` | 328 |
| `1` | 286 |
| `P@ssw0rd` | 242 |
| `admin123` | 238 |
| `password` | 175 |
| `123456789` | 146 |
| `000000` | 139 |
| `1111` | 135 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1564 |
| `cat` | 1345 |
| `cd` | 1339 |
| `echo` | 1319 |
| `crontab` | 1286 |
| `lscpu` | 1281 |
| `ls` | 1172 |
| `whoami` | 1167 |
| `free` | 1166 |
| `df` | 1164 |
| `top` | 1162 |
| `w` | 1162 |
| `INFO` | 717 |
| `PING` | 552 |
| `canary_env` | 450 |


_Generated from first-party honeypot capture. CC BY 4.0._
