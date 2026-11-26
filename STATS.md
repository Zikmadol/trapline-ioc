# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6266 attackers** · **1,365,774 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 342 |
| Used a planted canary credential | 269 |
| Seen on more than one sensor | 514 |
| Stage-2 hosts named in payloads | 73 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13585 |
| `ssh-bruteforce` | 1947 |
| `ssh-exploit` | 1470 |
| `redis-exploit` | 1139 |
| `mcp-abuse` | 349 |
| `docker-abuse` | 222 |
| `llamacpp-abuse` | 221 |
| `litellm-key-replay` | 204 |
| `ollama-abuse` | 169 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 32 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3581 |
| `redis` | 1171 |
| `mcp` | 693 |
| `llamacpp` | 617 |
| `vllm` | 486 |
| `litellm` | 429 |
| `docker` | 373 |
| `jupyter` | 326 |
| `ollama` | 301 |
| `hfhub` | 264 |
| `php` | 196 |
| `ray` | 68 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1939 |
| `345gs5662d34` | 1107 |
| `admin` | 955 |
| `ubuntu` | 441 |
| `guest` | 241 |
| `ftpuser` | 234 |
| `user` | 222 |
| `test` | 174 |
| `ftp` | 149 |
| `config` | 134 |
| `deploy` | 129 |
| `git` | 125 |
| `bin` | 118 |
| `administrator` | 117 |
| `george` | 116 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1096 |
| `123456` | 1042 |
| `123` | 635 |
| `1234` | 529 |
| `admin` | 418 |
| `12345678` | 410 |
| `12345` | 356 |
| `1` | 303 |
| `admin123` | 264 |
| `P@ssw0rd` | 256 |
| `password` | 174 |
| `1111` | 153 |
| `123456789` | 151 |
| `000000` | 147 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1608 |
| `cat` | 1379 |
| `cd` | 1374 |
| `echo` | 1347 |
| `crontab` | 1314 |
| `lscpu` | 1307 |
| `ls` | 1196 |
| `free` | 1190 |
| `whoami` | 1190 |
| `df` | 1187 |
| `top` | 1186 |
| `w` | 1186 |
| `INFO` | 804 |
| `PING` | 628 |
| `canary_env` | 588 |


_Generated from first-party honeypot capture. CC BY 4.0._
