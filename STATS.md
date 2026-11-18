# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5686 attackers** · **1,218,370 hostile actions** · covering 67 day(s) through 2026-11-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 312 |
| Used a planted canary credential | 234 |
| Seen on more than one sensor | 471 |
| Stage-2 hosts named in payloads | 63 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11929 |
| `ssh-bruteforce` | 1829 |
| `ssh-exploit` | 1437 |
| `redis-exploit` | 1013 |
| `mcp-abuse` | 318 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 176 |
| `ollama-abuse` | 153 |
| `llamacpp-abuse` | 133 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3414 |
| `redis` | 1045 |
| `mcp` | 549 |
| `llamacpp` | 450 |
| `vllm` | 343 |
| `litellm` | 341 |
| `docker` | 309 |
| `jupyter` | 282 |
| `ollama` | 274 |
| `hfhub` | 227 |
| `php` | 163 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1855 |
| `345gs5662d34` | 1103 |
| `admin` | 911 |
| `ubuntu` | 423 |
| `guest` | 224 |
| `ftpuser` | 219 |
| `user` | 217 |
| `test` | 174 |
| `ftp` | 133 |
| `git` | 123 |
| `deploy` | 123 |
| `config` | 118 |
| `support` | 113 |
| `postgres` | 112 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 998 |
| `123` | 613 |
| `1234` | 490 |
| `12345678` | 391 |
| `admin` | 386 |
| `12345` | 321 |
| `1` | 282 |
| `P@ssw0rd` | 241 |
| `admin123` | 236 |
| `password` | 176 |
| `123456789` | 145 |
| `000000` | 138 |
| `1111` | 132 |

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
