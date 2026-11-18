# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5674 attackers** · **1,217,689 hostile actions** · covering 67 day(s) through 2026-11-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 311 |
| Used a planted canary credential | 233 |
| Seen on more than one sensor | 471 |
| Stage-2 hosts named in payloads | 63 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11721 |
| `ssh-bruteforce` | 1825 |
| `ssh-exploit` | 1436 |
| `redis-exploit` | 1010 |
| `mcp-abuse` | 318 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 173 |
| `ollama-abuse` | 153 |
| `llamacpp-abuse` | 132 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3408 |
| `redis` | 1042 |
| `mcp` | 547 |
| `llamacpp` | 449 |
| `vllm` | 343 |
| `litellm` | 341 |
| `docker` | 306 |
| `jupyter` | 282 |
| `ollama` | 274 |
| `hfhub` | 227 |
| `php` | 163 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1852 |
| `345gs5662d34` | 1103 |
| `admin` | 911 |
| `ubuntu` | 422 |
| `guest` | 224 |
| `ftpuser` | 219 |
| `user` | 216 |
| `test` | 174 |
| `ftp` | 133 |
| `git` | 123 |
| `deploy` | 122 |
| `config` | 118 |
| `support` | 113 |
| `postgres` | 112 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 997 |
| `123` | 613 |
| `1234` | 489 |
| `12345678` | 391 |
| `admin` | 386 |
| `12345` | 320 |
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
| `uname` | 1556 |
| `cat` | 1339 |
| `cd` | 1333 |
| `echo` | 1313 |
| `crontab` | 1280 |
| `lscpu` | 1275 |
| `ls` | 1166 |
| `whoami` | 1161 |
| `free` | 1160 |
| `df` | 1158 |
| `top` | 1156 |
| `w` | 1156 |
| `INFO` | 715 |
| `PING` | 548 |
| `canary_env` | 447 |


_Generated from first-party honeypot capture. CC BY 4.0._
