# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6077 attackers** · **1,331,997 hostile actions** · covering 73 day(s) through 2026-11-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 334 |
| Used a planted canary credential | 261 |
| Seen on more than one sensor | 506 |
| Stage-2 hosts named in payloads | 71 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13551 |
| `ssh-bruteforce` | 1916 |
| `ssh-exploit` | 1464 |
| `redis-exploit` | 1099 |
| `mcp-abuse` | 344 |
| `docker-abuse` | 216 |
| `litellm-key-replay` | 191 |
| `ollama-abuse` | 165 |
| `llamacpp-abuse` | 156 |
| `jupyter-abuse` | 54 |
| `litellm-abuse` | 42 |
| `vllm-abuse` | 29 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3539 |
| `redis` | 1131 |
| `mcp` | 623 |
| `llamacpp` | 545 |
| `vllm` | 415 |
| `litellm` | 402 |
| `docker` | 363 |
| `jupyter` | 318 |
| `ollama` | 296 |
| `hfhub` | 258 |
| `php` | 189 |
| `ray` | 62 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1913 |
| `345gs5662d34` | 1106 |
| `admin` | 944 |
| `ubuntu` | 438 |
| `guest` | 236 |
| `ftpuser` | 229 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 144 |
| `config` | 129 |
| `deploy` | 129 |
| `git` | 125 |
| `administrator` | 116 |
| `support` | 114 |
| `postgres` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1034 |
| `123` | 633 |
| `1234` | 518 |
| `admin` | 408 |
| `12345678` | 407 |
| `12345` | 349 |
| `1` | 300 |
| `admin123` | 256 |
| `P@ssw0rd` | 252 |
| `password` | 172 |
| `123456789` | 151 |
| `1111` | 148 |
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
| `INFO` | 775 |
| `PING` | 602 |
| `canary_env` | 517 |


_Generated from first-party honeypot capture. CC BY 4.0._
