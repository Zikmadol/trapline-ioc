# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6116 attackers** · **1,339,728 hostile actions** · covering 73 day(s) through 2026-11-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 339 |
| Used a planted canary credential | 263 |
| Seen on more than one sensor | 507 |
| Stage-2 hosts named in payloads | 72 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13553 |
| `ssh-bruteforce` | 1923 |
| `ssh-exploit` | 1464 |
| `redis-exploit` | 1108 |
| `mcp-abuse` | 345 |
| `docker-abuse` | 218 |
| `litellm-key-replay` | 196 |
| `ollama-abuse` | 168 |
| `llamacpp-abuse` | 158 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 42 |
| `vllm-abuse` | 30 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3546 |
| `redis` | 1140 |
| `mcp` | 626 |
| `llamacpp` | 550 |
| `vllm` | 418 |
| `litellm` | 410 |
| `docker` | 366 |
| `jupyter` | 322 |
| `ollama` | 299 |
| `hfhub` | 259 |
| `php` | 192 |
| `ray` | 68 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1916 |
| `345gs5662d34` | 1106 |
| `admin` | 948 |
| `ubuntu` | 438 |
| `guest` | 238 |
| `ftpuser` | 231 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 146 |
| `config` | 131 |
| `deploy` | 129 |
| `git` | 125 |
| `administrator` | 116 |
| `bin` | 115 |
| `support` | 114 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1038 |
| `123` | 633 |
| `1234` | 520 |
| `admin` | 414 |
| `12345678` | 409 |
| `12345` | 352 |
| `1` | 301 |
| `admin123` | 258 |
| `P@ssw0rd` | 254 |
| `password` | 173 |
| `123456789` | 152 |
| `1111` | 150 |
| `000000` | 145 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1599 |
| `cat` | 1372 |
| `cd` | 1367 |
| `echo` | 1339 |
| `crontab` | 1306 |
| `lscpu` | 1299 |
| `ls` | 1189 |
| `free` | 1183 |
| `whoami` | 1183 |
| `df` | 1180 |
| `top` | 1179 |
| `w` | 1179 |
| `INFO` | 781 |
| `PING` | 607 |
| `canary_env` | 521 |


_Generated from first-party honeypot capture. CC BY 4.0._
