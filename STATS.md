# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4535 attackers** · **1,031,930 hostile actions** · covering 59 day(s) through 2026-11-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 226 |
| Used a planted canary credential | 153 |
| Seen on more than one sensor | 353 |
| Stage-2 hosts named in payloads | 59 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 8064 |
| `ssh-exploit` | 1387 |
| `ssh-bruteforce` | 1187 |
| `redis-exploit` | 872 |
| `mcp-abuse` | 290 |
| `litellm-key-replay` | 158 |
| `ollama-abuse` | 123 |
| `llamacpp-abuse` | 109 |
| `docker-abuse` | 64 |
| `jupyter-abuse` | 50 |
| `php-abuse` | 19 |
| `vllm-abuse` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2690 |
| `redis` | 898 |
| `mcp` | 484 |
| `llamacpp` | 364 |
| `litellm` | 284 |
| `vllm` | 242 |
| `jupyter` | 237 |
| `ollama` | 209 |
| `hfhub` | 180 |
| `docker` | 169 |
| `php` | 110 |
| `ray` | 41 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1644 |
| `345gs5662d34` | 1098 |
| `admin` | 809 |
| `ubuntu` | 408 |
| `ftpuser` | 199 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 141 |
| `git` | 117 |
| `deploy` | 113 |
| `ftp` | 112 |
| `postgres` | 108 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 85 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 930 |
| `123` | 597 |
| `1234` | 431 |
| `12345678` | 359 |
| `admin` | 330 |
| `12345` | 274 |
| `1` | 269 |
| `admin123` | 208 |
| `P@ssw0rd` | 208 |
| `password` | 160 |
| `123456789` | 133 |
| `000000` | 132 |
| `!QAZ2wsx` | 119 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1505 |
| `cd` | 1299 |
| `cat` | 1297 |
| `echo` | 1269 |
| `crontab` | 1242 |
| `lscpu` | 1239 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 616 |
| `PING` | 460 |
| `canary_env` | 392 |


_Generated from first-party honeypot capture. CC BY 4.0._
