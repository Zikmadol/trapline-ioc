# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5540 attackers** · **1,204,737 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 301 |
| Used a planted canary credential | 230 |
| Seen on more than one sensor | 456 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11149 |
| `ssh-bruteforce` | 1737 |
| `ssh-exploit` | 1429 |
| `redis-exploit` | 1000 |
| `mcp-abuse` | 312 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 163 |
| `ollama-abuse` | 150 |
| `llamacpp-abuse` | 130 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3311 |
| `redis` | 1032 |
| `mcp` | 538 |
| `llamacpp` | 433 |
| `litellm` | 336 |
| `vllm` | 331 |
| `docker` | 292 |
| `jupyter` | 278 |
| `ollama` | 264 |
| `hfhub` | 223 |
| `php` | 160 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1807 |
| `345gs5662d34` | 1101 |
| `admin` | 898 |
| `ubuntu` | 421 |
| `ftpuser` | 217 |
| `guest` | 216 |
| `user` | 215 |
| `test` | 174 |
| `ftp` | 131 |
| `git` | 121 |
| `deploy` | 119 |
| `postgres` | 111 |
| `config` | 110 |
| `support` | 108 |
| `administrator` | 107 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1099 |
| `3245gs5662d34` | 1091 |
| `123456` | 987 |
| `123` | 611 |
| `1234` | 479 |
| `12345678` | 387 |
| `admin` | 377 |
| `12345` | 308 |
| `1` | 280 |
| `P@ssw0rd` | 236 |
| `admin123` | 235 |
| `password` | 172 |
| `123456789` | 144 |
| `000000` | 138 |
| `1111` | 130 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1545 |
| `cat` | 1328 |
| `cd` | 1322 |
| `echo` | 1302 |
| `crontab` | 1268 |
| `lscpu` | 1265 |
| `ls` | 1156 |
| `whoami` | 1151 |
| `free` | 1149 |
| `df` | 1147 |
| `top` | 1146 |
| `w` | 1146 |
| `INFO` | 713 |
| `PING` | 544 |
| `canary_env` | 439 |


_Generated from first-party honeypot capture. CC BY 4.0._
