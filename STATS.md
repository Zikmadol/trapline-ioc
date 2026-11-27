# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6518 attackers** · **1,404,569 hostile actions** · covering 76 day(s) through 2026-11-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 352 |
| Used a planted canary credential | 277 |
| Seen on more than one sensor | 531 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13609 |
| `ssh-bruteforce` | 2017 |
| `ssh-exploit` | 1489 |
| `redis-exploit` | 1215 |
| `mcp-abuse` | 365 |
| `docker-abuse` | 233 |
| `litellm-key-replay` | 231 |
| `llamacpp-abuse` | 228 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 59 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3675 |
| `redis` | 1248 |
| `mcp` | 719 |
| `llamacpp` | 640 |
| `vllm` | 507 |
| `litellm` | 462 |
| `docker` | 394 |
| `jupyter` | 342 |
| `ollama` | 313 |
| `hfhub` | 273 |
| `php` | 209 |
| `ray` | 80 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 2007 |
| `345gs5662d34` | 1108 |
| `admin` | 968 |
| `ubuntu` | 439 |
| `guest` | 246 |
| `ftpuser` | 240 |
| `user` | 226 |
| `test` | 177 |
| `ftp` | 154 |
| `config` | 139 |
| `deploy` | 132 |
| `git` | 127 |
| `bin` | 122 |
| `george` | 121 |
| `administrator` | 120 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1098 |
| `123456` | 1060 |
| `123` | 648 |
| `1234` | 546 |
| `admin` | 425 |
| `12345678` | 417 |
| `12345` | 362 |
| `1` | 304 |
| `admin123` | 268 |
| `P@ssw0rd` | 261 |
| `password` | 177 |
| `1111` | 156 |
| `123456789` | 152 |
| `000000` | 149 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1639 |
| `cat` | 1408 |
| `cd` | 1401 |
| `echo` | 1375 |
| `crontab` | 1342 |
| `lscpu` | 1334 |
| `ls` | 1223 |
| `free` | 1216 |
| `whoami` | 1216 |
| `df` | 1213 |
| `top` | 1212 |
| `w` | 1212 |
| `INFO` | 872 |
| `PING` | 696 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
