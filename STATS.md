# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6050 attackers** · **1,330,961 hostile actions** · covering 72 day(s) through 2026-11-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 333 |
| Used a planted canary credential | 261 |
| Seen on more than one sensor | 505 |
| Stage-2 hosts named in payloads | 71 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13548 |
| `ssh-bruteforce` | 1912 |
| `ssh-exploit` | 1464 |
| `redis-exploit` | 1088 |
| `mcp-abuse` | 338 |
| `docker-abuse` | 214 |
| `litellm-key-replay` | 191 |
| `ollama-abuse` | 164 |
| `llamacpp-abuse` | 156 |
| `jupyter-abuse` | 53 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 29 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3534 |
| `redis` | 1120 |
| `mcp` | 612 |
| `llamacpp` | 537 |
| `vllm` | 409 |
| `litellm` | 399 |
| `docker` | 361 |
| `jupyter` | 314 |
| `ollama` | 295 |
| `hfhub` | 255 |
| `php` | 188 |
| `ray` | 60 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1912 |
| `345gs5662d34` | 1106 |
| `admin` | 942 |
| `ubuntu` | 438 |
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
| `123456` | 1033 |
| `123` | 633 |
| `1234` | 517 |
| `admin` | 406 |
| `12345678` | 406 |
| `12345` | 348 |
| `1` | 300 |
| `admin123` | 256 |
| `P@ssw0rd` | 250 |
| `password` | 172 |
| `123456789` | 150 |
| `1111` | 147 |
| `000000` | 144 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1598 |
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
| `INFO` | 769 |
| `PING` | 596 |
| `canary_env` | 510 |


_Generated from first-party honeypot capture. CC BY 4.0._
