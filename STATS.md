# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5639 attackers** · **1,209,503 hostile actions** · covering 67 day(s) through 2026-11-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 310 |
| Used a planted canary credential | 230 |
| Seen on more than one sensor | 470 |
| Stage-2 hosts named in payloads | 63 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11391 |
| `ssh-bruteforce` | 1803 |
| `ssh-exploit` | 1433 |
| `redis-exploit` | 1009 |
| `mcp-abuse` | 316 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 172 |
| `ollama-abuse` | 152 |
| `llamacpp-abuse` | 131 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3383 |
| `redis` | 1041 |
| `mcp` | 545 |
| `llamacpp` | 446 |
| `vllm` | 343 |
| `litellm` | 339 |
| `docker` | 305 |
| `jupyter` | 282 |
| `ollama` | 273 |
| `hfhub` | 226 |
| `php` | 161 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1841 |
| `345gs5662d34` | 1103 |
| `admin` | 906 |
| `ubuntu` | 424 |
| `guest` | 223 |
| `ftpuser` | 218 |
| `user` | 216 |
| `test` | 174 |
| `ftp` | 132 |
| `git` | 123 |
| `deploy` | 120 |
| `postgres` | 112 |
| `config` | 111 |
| `support` | 111 |
| `administrator` | 108 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 994 |
| `123` | 613 |
| `1234` | 484 |
| `12345678` | 390 |
| `admin` | 384 |
| `12345` | 315 |
| `1` | 281 |
| `P@ssw0rd` | 238 |
| `admin123` | 236 |
| `password` | 174 |
| `123456789` | 145 |
| `000000` | 138 |
| `1111` | 131 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1550 |
| `cat` | 1333 |
| `cd` | 1327 |
| `echo` | 1307 |
| `crontab` | 1274 |
| `lscpu` | 1269 |
| `ls` | 1160 |
| `whoami` | 1155 |
| `free` | 1154 |
| `df` | 1152 |
| `top` | 1150 |
| `w` | 1150 |
| `INFO` | 715 |
| `PING` | 547 |
| `canary_env` | 444 |


_Generated from first-party honeypot capture. CC BY 4.0._
