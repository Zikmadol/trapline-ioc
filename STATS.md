# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5100 attackers** · **1,157,217 hostile actions** · covering 63 day(s) through 2026-11-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 294 |
| Used a planted canary credential | 180 |
| Seen on more than one sensor | 435 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10182 |
| `ssh-bruteforce` | 1465 |
| `ssh-exploit` | 1402 |
| `redis-exploit` | 960 |
| `mcp-abuse` | 303 |
| `litellm-key-replay` | 166 |
| `docker-abuse` | 156 |
| `ollama-abuse` | 142 |
| `llamacpp-abuse` | 120 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 23 |
| `php-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3003 |
| `redis` | 991 |
| `mcp` | 520 |
| `llamacpp` | 407 |
| `litellm` | 315 |
| `vllm` | 311 |
| `docker` | 279 |
| `jupyter` | 263 |
| `ollama` | 247 |
| `hfhub` | 210 |
| `php` | 148 |
| `ray` | 46 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1719 |
| `345gs5662d34` | 1098 |
| `admin` | 876 |
| `ubuntu` | 414 |
| `ftpuser` | 211 |
| `user` | 203 |
| `guest` | 170 |
| `test` | 164 |
| `ftp` | 125 |
| `git` | 119 |
| `deploy` | 116 |
| `postgres` | 111 |
| `administrator` | 106 |
| `config` | 96 |
| `bin` | 92 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 956 |
| `123` | 602 |
| `1234` | 462 |
| `12345678` | 380 |
| `admin` | 354 |
| `12345` | 293 |
| `1` | 274 |
| `admin123` | 229 |
| `P@ssw0rd` | 222 |
| `password` | 169 |
| `123456789` | 142 |
| `000000` | 133 |
| `!QAZ2wsx` | 125 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1514 |
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
| `INFO` | 685 |
| `PING` | 525 |
| `canary_env` | 418 |


_Generated from first-party honeypot capture. CC BY 4.0._
