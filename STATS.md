# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6553 attackers** · **1,409,555 hostile actions** · covering 77 day(s) through 2026-11-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 352 |
| Used a planted canary credential | 278 |
| Seen on more than one sensor | 531 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13615 |
| `ssh-bruteforce` | 2026 |
| `ssh-exploit` | 1493 |
| `redis-exploit` | 1228 |
| `mcp-abuse` | 365 |
| `litellm-key-replay` | 237 |
| `docker-abuse` | 234 |
| `llamacpp-abuse` | 228 |
| `ollama-abuse` | 171 |
| `jupyter-abuse` | 59 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3688 |
| `redis` | 1261 |
| `mcp` | 721 |
| `llamacpp` | 640 |
| `vllm` | 509 |
| `litellm` | 470 |
| `docker` | 395 |
| `jupyter` | 344 |
| `ollama` | 314 |
| `hfhub` | 275 |
| `php` | 210 |
| `ray` | 80 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 2016 |
| `345gs5662d34` | 1109 |
| `admin` | 970 |
| `ubuntu` | 438 |
| `guest` | 246 |
| `ftpuser` | 240 |
| `user` | 226 |
| `test` | 177 |
| `ftp` | 154 |
| `config` | 139 |
| `deploy` | 132 |
| `git` | 128 |
| `bin` | 122 |
| `administrator` | 121 |
| `george` | 120 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1105 |
| `3245gs5662d34` | 1097 |
| `123456` | 1062 |
| `123` | 648 |
| `1234` | 546 |
| `admin` | 425 |
| `12345678` | 417 |
| `12345` | 362 |
| `1` | 303 |
| `admin123` | 268 |
| `P@ssw0rd` | 260 |
| `password` | 178 |
| `1111` | 156 |
| `123456789` | 154 |
| `000000` | 150 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1645 |
| `cat` | 1413 |
| `cd` | 1406 |
| `echo` | 1380 |
| `crontab` | 1347 |
| `lscpu` | 1338 |
| `ls` | 1228 |
| `free` | 1221 |
| `whoami` | 1220 |
| `df` | 1217 |
| `w` | 1217 |
| `top` | 1216 |
| `INFO` | 883 |
| `PING` | 707 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
