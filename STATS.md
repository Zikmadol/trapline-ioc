# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5690 attackers** · **1,218,667 hostile actions** · covering 67 day(s) through 2026-11-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 312 |
| Used a planted canary credential | 234 |
| Seen on more than one sensor | 472 |
| Stage-2 hosts named in payloads | 63 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 12005 |
| `ssh-bruteforce` | 1831 |
| `ssh-exploit` | 1437 |
| `redis-exploit` | 1013 |
| `mcp-abuse` | 318 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 178 |
| `ollama-abuse` | 153 |
| `llamacpp-abuse` | 133 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3416 |
| `redis` | 1045 |
| `mcp` | 550 |
| `llamacpp` | 450 |
| `vllm` | 343 |
| `litellm` | 343 |
| `docker` | 311 |
| `jupyter` | 282 |
| `ollama` | 274 |
| `hfhub` | 227 |
| `php` | 163 |
| `ray` | 51 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1856 |
| `345gs5662d34` | 1103 |
| `admin` | 912 |
| `ubuntu` | 423 |
| `guest` | 225 |
| `ftpuser` | 220 |
| `user` | 217 |
| `test` | 174 |
| `ftp` | 134 |
| `git` | 123 |
| `deploy` | 123 |
| `config` | 119 |
| `support` | 113 |
| `postgres` | 112 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 999 |
| `123` | 613 |
| `1234` | 491 |
| `12345678` | 392 |
| `admin` | 387 |
| `12345` | 322 |
| `1` | 282 |
| `P@ssw0rd` | 242 |
| `admin123` | 237 |
| `password` | 176 |
| `123456789` | 145 |
| `000000` | 138 |
| `1111` | 133 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1558 |
| `cat` | 1340 |
| `cd` | 1334 |
| `echo` | 1314 |
| `crontab` | 1281 |
| `lscpu` | 1276 |
| `ls` | 1167 |
| `whoami` | 1162 |
| `free` | 1161 |
| `df` | 1159 |
| `top` | 1157 |
| `w` | 1157 |
| `INFO` | 716 |
| `PING` | 550 |
| `canary_env` | 448 |


_Generated from first-party honeypot capture. CC BY 4.0._
