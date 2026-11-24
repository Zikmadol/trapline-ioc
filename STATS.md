# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6112 attackers** · **1,339,507 hostile actions** · covering 73 day(s) through 2026-11-24

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
| `ssh-bruteforce` | 1921 |
| `ssh-exploit` | 1464 |
| `redis-exploit` | 1107 |
| `mcp-abuse` | 345 |
| `docker-abuse` | 218 |
| `litellm-key-replay` | 195 |
| `ollama-abuse` | 168 |
| `llamacpp-abuse` | 158 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 42 |
| `vllm-abuse` | 30 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3544 |
| `redis` | 1139 |
| `mcp` | 626 |
| `llamacpp` | 550 |
| `vllm` | 418 |
| `litellm` | 408 |
| `docker` | 366 |
| `jupyter` | 322 |
| `ollama` | 299 |
| `hfhub` | 259 |
| `php` | 192 |
| `ray` | 68 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1915 |
| `345gs5662d34` | 1106 |
| `admin` | 947 |
| `ubuntu` | 438 |
| `guest` | 237 |
| `ftpuser` | 230 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 145 |
| `config` | 130 |
| `deploy` | 129 |
| `git` | 125 |
| `administrator` | 116 |
| `support` | 114 |
| `bin` | 114 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1037 |
| `123` | 633 |
| `1234` | 519 |
| `admin` | 412 |
| `12345678` | 408 |
| `12345` | 351 |
| `1` | 301 |
| `admin123` | 257 |
| `P@ssw0rd` | 253 |
| `password` | 173 |
| `123456789` | 152 |
| `1111` | 149 |
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
| `INFO` | 780 |
| `PING` | 606 |
| `canary_env` | 521 |


_Generated from first-party honeypot capture. CC BY 4.0._
