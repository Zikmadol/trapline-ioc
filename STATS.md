# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5776 attackers** · **1,247,365 hostile actions** · covering 68 day(s) through 2026-11-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 316 |
| Used a planted canary credential | 238 |
| Seen on more than one sensor | 481 |
| Stage-2 hosts named in payloads | 66 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13252 |
| `ssh-bruteforce` | 1855 |
| `ssh-exploit` | 1448 |
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
| `ssh` | 3454 |
| `redis` | 1067 |
| `mcp` | 561 |
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
| `root` | 1878 |
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
| `support` | 113 |
| `administrator` | 111 |
| `postgres` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 1010 |
| `123` | 616 |
| `1234` | 498 |
| `12345678` | 394 |
| `admin` | 389 |
| `12345` | 332 |
| `1` | 289 |
| `P@ssw0rd` | 243 |
| `admin123` | 239 |
| `password` | 173 |
| `123456789` | 146 |
| `000000` | 141 |
| `1111` | 141 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1572 |
| `cat` | 1352 |
| `cd` | 1345 |
| `echo` | 1326 |
| `crontab` | 1293 |
| `lscpu` | 1288 |
| `ls` | 1178 |
| `whoami` | 1173 |
| `free` | 1172 |
| `df` | 1170 |
| `top` | 1168 |
| `w` | 1168 |
| `INFO` | 730 |
| `PING` | 561 |
| `canary_env` | 454 |


_Generated from first-party honeypot capture. CC BY 4.0._
