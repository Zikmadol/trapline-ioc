# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6529 attackers** · **1,407,980 hostile actions** · covering 76 day(s) through 2026-11-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 352 |
| Used a planted canary credential | 278 |
| Seen on more than one sensor | 531 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13610 |
| `ssh-bruteforce` | 2019 |
| `ssh-exploit` | 1489 |
| `redis-exploit` | 1219 |
| `mcp-abuse` | 365 |
| `litellm-key-replay` | 235 |
| `docker-abuse` | 233 |
| `llamacpp-abuse` | 228 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 59 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3677 |
| `redis` | 1252 |
| `mcp` | 719 |
| `llamacpp` | 640 |
| `vllm` | 508 |
| `litellm` | 466 |
| `docker` | 394 |
| `jupyter` | 342 |
| `ollama` | 313 |
| `hfhub` | 274 |
| `php` | 209 |
| `ray` | 80 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 2009 |
| `345gs5662d34` | 1108 |
| `admin` | 968 |
| `ubuntu` | 438 |
| `guest` | 246 |
| `ftpuser` | 240 |
| `user` | 226 |
| `test` | 177 |
| `ftp` | 154 |
| `config` | 139 |
| `deploy` | 132 |
| `git` | 127 |
| `bin` | 122 |
| `administrator` | 121 |
| `george` | 120 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1098 |
| `123456` | 1060 |
| `123` | 647 |
| `1234` | 546 |
| `admin` | 425 |
| `12345678` | 417 |
| `12345` | 362 |
| `1` | 303 |
| `admin123` | 268 |
| `P@ssw0rd` | 261 |
| `password` | 178 |
| `1111` | 156 |
| `123456789` | 152 |
| `000000` | 150 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1640 |
| `cat` | 1409 |
| `cd` | 1402 |
| `echo` | 1376 |
| `crontab` | 1343 |
| `lscpu` | 1335 |
| `ls` | 1224 |
| `free` | 1217 |
| `whoami` | 1217 |
| `df` | 1214 |
| `top` | 1213 |
| `w` | 1213 |
| `INFO` | 876 |
| `PING` | 699 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
