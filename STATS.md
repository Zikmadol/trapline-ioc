# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5211 attackers** · **1,176,258 hostile actions** · covering 64 day(s) through 2026-11-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 297 |
| Used a planted canary credential | 191 |
| Seen on more than one sensor | 440 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10509 |
| `ssh-bruteforce` | 1534 |
| `ssh-exploit` | 1403 |
| `redis-exploit` | 974 |
| `mcp-abuse` | 303 |
| `litellm-key-replay` | 177 |
| `docker-abuse` | 158 |
| `ollama-abuse` | 142 |
| `llamacpp-abuse` | 123 |
| `jupyter-abuse` | 50 |
| `php-abuse` | 24 |
| `vllm-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3077 |
| `redis` | 1006 |
| `mcp` | 522 |
| `llamacpp` | 415 |
| `litellm` | 328 |
| `vllm` | 321 |
| `docker` | 282 |
| `jupyter` | 270 |
| `ollama` | 252 |
| `hfhub` | 214 |
| `php` | 151 |
| `ray` | 47 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1730 |
| `345gs5662d34` | 1098 |
| `admin` | 884 |
| `ubuntu` | 415 |
| `ftpuser` | 213 |
| `user` | 205 |
| `guest` | 185 |
| `test` | 165 |
| `ftp` | 127 |
| `git` | 119 |
| `deploy` | 116 |
| `postgres` | 111 |
| `administrator` | 106 |
| `config` | 102 |
| `bin` | 94 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 961 |
| `123` | 602 |
| `1234` | 465 |
| `12345678` | 383 |
| `admin` | 360 |
| `12345` | 296 |
| `1` | 277 |
| `admin123` | 231 |
| `P@ssw0rd` | 224 |
| `password` | 174 |
| `123456789` | 143 |
| `000000` | 135 |
| `!QAZ2wsx` | 127 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1516 |
| `cat` | 1303 |
| `cd` | 1299 |
| `echo` | 1276 |
| `crontab` | 1245 |
| `lscpu` | 1242 |
| `ls` | 1131 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1124 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 694 |
| `PING` | 531 |
| `canary_env` | 422 |


_Generated from first-party honeypot capture. CC BY 4.0._
