# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4015 attackers** · **799,068 hostile actions** · covering 51 day(s) through 2026-11-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 210 |
| Used a planted canary credential | 63 |
| Seen on more than one sensor | 295 |
| Stage-2 hosts named in payloads | 55 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5564 |
| `ssh-exploit` | 1355 |
| `ssh-bruteforce` | 1127 |
| `redis-exploit` | 696 |
| `mcp-abuse` | 269 |
| `litellm-key-replay` | 110 |
| `llamacpp-abuse` | 92 |
| `ollama-abuse` | 84 |
| `docker-abuse` | 55 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 16 |
| `vllm-key-replay` | 15 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2577 |
| `redis` | 715 |
| `mcp` | 418 |
| `llamacpp` | 291 |
| `litellm` | 208 |
| `vllm` | 182 |
| `jupyter` | 177 |
| `ollama` | 140 |
| `docker` | 138 |
| `hfhub` | 136 |
| `php` | 74 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1599 |
| `345gs5662d34` | 1098 |
| `admin` | 764 |
| `ubuntu` | 385 |
| `user` | 188 |
| `ftpuser` | 185 |
| `test` | 146 |
| `guest` | 123 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 109 |
| `administrator` | 100 |
| `ftp` | 98 |
| `oracle` | 86 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 897 |
| `123` | 584 |
| `1234` | 415 |
| `12345678` | 334 |
| `admin` | 297 |
| `1` | 263 |
| `12345` | 261 |
| `P@ssw0rd` | 193 |
| `admin123` | 185 |
| `password` | 157 |
| `123456789` | 132 |
| `000000` | 126 |
| `!QAZ2wsx` | 111 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1476 |
| `cd` | 1280 |
| `cat` | 1278 |
| `echo` | 1261 |
| `crontab` | 1236 |
| `lscpu` | 1233 |
| `ls` | 1128 |
| `free` | 1126 |
| `whoami` | 1124 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 472 |
| `canary_env` | 351 |
| `PING` | 336 |


_Generated from first-party honeypot capture. CC BY 4.0._
