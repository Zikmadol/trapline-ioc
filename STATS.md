# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5594 attackers** · **1,207,334 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 310 |
| Used a planted canary credential | 230 |
| Seen on more than one sensor | 470 |
| Stage-2 hosts named in payloads | 62 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11273 |
| `ssh-bruteforce` | 1767 |
| `ssh-exploit` | 1432 |
| `redis-exploit` | 1006 |
| `mcp-abuse` | 315 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 172 |
| `ollama-abuse` | 150 |
| `llamacpp-abuse` | 130 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3346 |
| `redis` | 1038 |
| `mcp` | 543 |
| `llamacpp` | 443 |
| `vllm` | 340 |
| `litellm` | 337 |
| `docker` | 305 |
| `jupyter` | 281 |
| `ollama` | 271 |
| `hfhub` | 225 |
| `php` | 161 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1823 |
| `345gs5662d34` | 1101 |
| `admin` | 901 |
| `ubuntu` | 423 |
| `guest` | 221 |
| `ftpuser` | 218 |
| `user` | 216 |
| `test` | 174 |
| `ftp` | 132 |
| `git` | 123 |
| `deploy` | 119 |
| `postgres` | 112 |
| `support` | 112 |
| `config` | 111 |
| `administrator` | 108 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1099 |
| `3245gs5662d34` | 1091 |
| `123456` | 992 |
| `123` | 612 |
| `1234` | 481 |
| `12345678` | 389 |
| `admin` | 379 |
| `12345` | 311 |
| `1` | 280 |
| `P@ssw0rd` | 237 |
| `admin123` | 236 |
| `password` | 173 |
| `123456789` | 144 |
| `000000` | 138 |
| `1111` | 131 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1547 |
| `cat` | 1331 |
| `cd` | 1325 |
| `echo` | 1305 |
| `crontab` | 1271 |
| `lscpu` | 1267 |
| `ls` | 1158 |
| `whoami` | 1153 |
| `free` | 1152 |
| `df` | 1150 |
| `top` | 1148 |
| `w` | 1148 |
| `INFO` | 713 |
| `PING` | 546 |
| `canary_env` | 442 |


_Generated from first-party honeypot capture. CC BY 4.0._
