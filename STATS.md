# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5919 attackers** · **1,301,228 hostile actions** · covering 71 day(s) through 2026-11-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 326 |
| Used a planted canary credential | 246 |
| Seen on more than one sensor | 494 |
| Stage-2 hosts named in payloads | 68 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13510 |
| `ssh-bruteforce` | 1902 |
| `ssh-exploit` | 1460 |
| `redis-exploit` | 1062 |
| `mcp-abuse` | 330 |
| `docker-abuse` | 205 |
| `litellm-key-replay` | 188 |
| `ollama-abuse` | 161 |
| `llamacpp-abuse` | 138 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 27 |
| `php-abuse` | 27 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3517 |
| `redis` | 1094 |
| `mcp` | 575 |
| `llamacpp` | 479 |
| `litellm` | 364 |
| `vllm` | 363 |
| `docker` | 345 |
| `jupyter` | 300 |
| `ollama` | 287 |
| `hfhub` | 242 |
| `php` | 178 |
| `ray` | 56 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1908 |
| `345gs5662d34` | 1106 |
| `admin` | 934 |
| `ubuntu` | 434 |
| `guest` | 232 |
| `ftpuser` | 225 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 140 |
| `deploy` | 128 |
| `config` | 125 |
| `git` | 125 |
| `administrator` | 116 |
| `support` | 114 |
| `postgres` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1027 |
| `123` | 629 |
| `1234` | 511 |
| `12345678` | 401 |
| `admin` | 398 |
| `12345` | 345 |
| `1` | 295 |
| `admin123` | 249 |
| `P@ssw0rd` | 247 |
| `password` | 172 |
| `123456789` | 149 |
| `000000` | 144 |
| `1111` | 144 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1593 |
| `cat` | 1369 |
| `cd` | 1364 |
| `echo` | 1339 |
| `crontab` | 1305 |
| `lscpu` | 1299 |
| `ls` | 1189 |
| `free` | 1183 |
| `whoami` | 1183 |
| `df` | 1180 |
| `top` | 1179 |
| `w` | 1179 |
| `INFO` | 750 |
| `PING` | 578 |
| `canary_env` | 462 |


_Generated from first-party honeypot capture. CC BY 4.0._
