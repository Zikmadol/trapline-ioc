# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6010 attackers** · **1,329,650 hostile actions** · covering 72 day(s) through 2026-11-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 332 |
| Used a planted canary credential | 251 |
| Seen on more than one sensor | 500 |
| Stage-2 hosts named in payloads | 69 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13526 |
| `ssh-bruteforce` | 1909 |
| `ssh-exploit` | 1462 |
| `redis-exploit` | 1083 |
| `mcp-abuse` | 334 |
| `docker-abuse` | 213 |
| `litellm-key-replay` | 191 |
| `ollama-abuse` | 163 |
| `llamacpp-abuse` | 150 |
| `jupyter-abuse` | 53 |
| `litellm-abuse` | 37 |
| `vllm-abuse` | 29 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3528 |
| `redis` | 1115 |
| `mcp` | 604 |
| `llamacpp` | 521 |
| `vllm` | 394 |
| `litellm` | 392 |
| `docker` | 359 |
| `jupyter` | 310 |
| `ollama` | 294 |
| `hfhub` | 252 |
| `php` | 184 |
| `ray` | 60 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1910 |
| `345gs5662d34` | 1106 |
| `admin` | 940 |
| `ubuntu` | 436 |
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
| `123456` | 1032 |
| `123` | 631 |
| `1234` | 517 |
| `12345678` | 406 |
| `admin` | 405 |
| `12345` | 348 |
| `1` | 299 |
| `admin123` | 254 |
| `P@ssw0rd` | 250 |
| `password` | 173 |
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
| `INFO` | 765 |
| `PING` | 592 |
| `canary_env` | 495 |


_Generated from first-party honeypot capture. CC BY 4.0._
