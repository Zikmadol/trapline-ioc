# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5943 attackers** · **1,309,741 hostile actions** · covering 71 day(s) through 2026-11-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 327 |
| Used a planted canary credential | 246 |
| Seen on more than one sensor | 498 |
| Stage-2 hosts named in payloads | 68 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13510 |
| `ssh-bruteforce` | 1906 |
| `ssh-exploit` | 1461 |
| `redis-exploit` | 1073 |
| `mcp-abuse` | 330 |
| `docker-abuse` | 208 |
| `litellm-key-replay` | 189 |
| `ollama-abuse` | 162 |
| `llamacpp-abuse` | 140 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 27 |
| `php-abuse` | 27 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3523 |
| `redis` | 1105 |
| `mcp` | 577 |
| `llamacpp` | 488 |
| `litellm` | 368 |
| `vllm` | 367 |
| `docker` | 350 |
| `jupyter` | 304 |
| `ollama` | 289 |
| `hfhub` | 247 |
| `php` | 181 |
| `ray` | 57 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1910 |
| `345gs5662d34` | 1106 |
| `admin` | 937 |
| `ubuntu` | 434 |
| `guest` | 233 |
| `ftpuser` | 226 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 141 |
| `deploy` | 129 |
| `config` | 126 |
| `git` | 125 |
| `administrator` | 116 |
| `support` | 114 |
| `postgres` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1029 |
| `123` | 630 |
| `1234` | 514 |
| `12345678` | 403 |
| `admin` | 401 |
| `12345` | 347 |
| `1` | 297 |
| `admin123` | 250 |
| `P@ssw0rd` | 248 |
| `password` | 172 |
| `123456789` | 150 |
| `1111` | 145 |
| `000000` | 144 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1594 |
| `cat` | 1369 |
| `cd` | 1364 |
| `echo` | 1339 |
| `crontab` | 1306 |
| `lscpu` | 1299 |
| `ls` | 1189 |
| `free` | 1183 |
| `whoami` | 1183 |
| `df` | 1180 |
| `top` | 1179 |
| `w` | 1179 |
| `INFO` | 758 |
| `PING` | 586 |
| `canary_env` | 464 |


_Generated from first-party honeypot capture. CC BY 4.0._
