# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5661 attackers** · **1,214,523 hostile actions** · covering 67 day(s) through 2026-11-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 310 |
| Used a planted canary credential | 232 |
| Seen on more than one sensor | 471 |
| Stage-2 hosts named in payloads | 63 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11602 |
| `ssh-bruteforce` | 1819 |
| `ssh-exploit` | 1434 |
| `redis-exploit` | 1010 |
| `mcp-abuse` | 318 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 172 |
| `ollama-abuse` | 152 |
| `llamacpp-abuse` | 130 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3400 |
| `redis` | 1042 |
| `mcp` | 547 |
| `llamacpp` | 447 |
| `vllm` | 343 |
| `litellm` | 341 |
| `docker` | 305 |
| `jupyter` | 282 |
| `ollama` | 273 |
| `hfhub` | 227 |
| `php` | 163 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1849 |
| `345gs5662d34` | 1103 |
| `admin` | 911 |
| `ubuntu` | 422 |
| `guest` | 224 |
| `ftpuser` | 219 |
| `user` | 217 |
| `test` | 174 |
| `ftp` | 133 |
| `git` | 123 |
| `deploy` | 121 |
| `config` | 116 |
| `postgres` | 112 |
| `support` | 111 |
| `administrator` | 110 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 996 |
| `123` | 613 |
| `1234` | 488 |
| `12345678` | 391 |
| `admin` | 386 |
| `12345` | 319 |
| `1` | 282 |
| `P@ssw0rd` | 239 |
| `admin123` | 236 |
| `password` | 176 |
| `123456789` | 145 |
| `000000` | 138 |
| `1111` | 132 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1552 |
| `cat` | 1335 |
| `cd` | 1329 |
| `echo` | 1309 |
| `crontab` | 1276 |
| `lscpu` | 1271 |
| `ls` | 1162 |
| `whoami` | 1157 |
| `free` | 1156 |
| `df` | 1154 |
| `top` | 1152 |
| `w` | 1152 |
| `INFO` | 715 |
| `PING` | 548 |
| `canary_env` | 446 |


_Generated from first-party honeypot capture. CC BY 4.0._
