# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5977 attackers** · **1,322,187 hostile actions** · covering 71 day(s) through 2026-11-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 328 |
| Used a planted canary credential | 250 |
| Seen on more than one sensor | 500 |
| Stage-2 hosts named in payloads | 69 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13525 |
| `ssh-bruteforce` | 1907 |
| `ssh-exploit` | 1462 |
| `redis-exploit` | 1079 |
| `mcp-abuse` | 333 |
| `docker-abuse` | 210 |
| `litellm-key-replay` | 188 |
| `ollama-abuse` | 162 |
| `llamacpp-abuse` | 142 |
| `jupyter-abuse` | 52 |
| `litellm-abuse` | 30 |
| `vllm-abuse` | 29 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3525 |
| `redis` | 1111 |
| `mcp` | 594 |
| `llamacpp` | 504 |
| `vllm` | 384 |
| `litellm` | 381 |
| `docker` | 353 |
| `jupyter` | 306 |
| `ollama` | 291 |
| `hfhub` | 249 |
| `php` | 182 |
| `ray` | 57 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1910 |
| `345gs5662d34` | 1106 |
| `admin` | 939 |
| `ubuntu` | 435 |
| `guest` | 234 |
| `ftpuser` | 227 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 142 |
| `deploy` | 129 |
| `config` | 127 |
| `git` | 125 |
| `administrator` | 116 |
| `support` | 114 |
| `postgres` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1030 |
| `123` | 631 |
| `1234` | 515 |
| `12345678` | 404 |
| `admin` | 402 |
| `12345` | 347 |
| `1` | 298 |
| `admin123` | 252 |
| `P@ssw0rd` | 249 |
| `password` | 172 |
| `123456789` | 150 |
| `1111` | 146 |
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
| `INFO` | 763 |
| `PING` | 590 |
| `canary_env` | 483 |


_Generated from first-party honeypot capture. CC BY 4.0._
