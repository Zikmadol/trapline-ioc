# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5782 attackers** · **1,252,751 hostile actions** · covering 69 day(s) through 2026-11-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 316 |
| Used a planted canary credential | 240 |
| Seen on more than one sensor | 482 |
| Stage-2 hosts named in payloads | 66 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13324 |
| `ssh-bruteforce` | 1858 |
| `ssh-exploit` | 1449 |
| `redis-exploit` | 1035 |
| `mcp-abuse` | 323 |
| `docker-abuse` | 184 |
| `litellm-key-replay` | 183 |
| `ollama-abuse` | 155 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 25 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3458 |
| `redis` | 1067 |
| `mcp` | 562 |
| `llamacpp` | 460 |
| `litellm` | 355 |
| `vllm` | 354 |
| `docker` | 320 |
| `jupyter` | 288 |
| `ollama` | 278 |
| `hfhub` | 235 |
| `php` | 167 |
| `ray` | 54 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1880 |
| `345gs5662d34` | 1104 |
| `admin` | 917 |
| `ubuntu` | 425 |
| `guest` | 228 |
| `ftpuser` | 222 |
| `user` | 218 |
| `test` | 174 |
| `ftp` | 136 |
| `deploy` | 124 |
| `git` | 123 |
| `config` | 121 |
| `support` | 114 |
| `administrator` | 111 |
| `postgres` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 1010 |
| `123` | 616 |
| `1234` | 500 |
| `12345678` | 394 |
| `admin` | 389 |
| `12345` | 332 |
| `1` | 289 |
| `P@ssw0rd` | 244 |
| `admin123` | 239 |
| `password` | 173 |
| `123456789` | 146 |
| `000000` | 141 |
| `1111` | 141 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1573 |
| `cat` | 1353 |
| `cd` | 1346 |
| `echo` | 1328 |
| `crontab` | 1294 |
| `lscpu` | 1289 |
| `ls` | 1179 |
| `whoami` | 1174 |
| `free` | 1173 |
| `df` | 1171 |
| `top` | 1169 |
| `w` | 1169 |
| `INFO` | 730 |
| `PING` | 561 |
| `canary_env` | 454 |


_Generated from first-party honeypot capture. CC BY 4.0._
