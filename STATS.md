# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5764 attackers** · **1,246,503 hostile actions** · covering 68 day(s) through 2026-11-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 316 |
| Used a planted canary credential | 238 |
| Seen on more than one sensor | 478 |
| Stage-2 hosts named in payloads | 65 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13151 |
| `ssh-bruteforce` | 1854 |
| `ssh-exploit` | 1448 |
| `redis-exploit` | 1027 |
| `mcp-abuse` | 322 |
| `docker-abuse` | 184 |
| `litellm-key-replay` | 183 |
| `ollama-abuse` | 155 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3452 |
| `redis` | 1059 |
| `mcp` | 558 |
| `llamacpp` | 458 |
| `litellm` | 353 |
| `vllm` | 349 |
| `docker` | 319 |
| `jupyter` | 286 |
| `ollama` | 278 |
| `hfhub` | 233 |
| `php` | 166 |
| `ray` | 54 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1879 |
| `345gs5662d34` | 1104 |
| `admin` | 916 |
| `ubuntu` | 425 |
| `guest` | 227 |
| `ftpuser` | 221 |
| `user` | 218 |
| `test` | 174 |
| `ftp` | 135 |
| `deploy` | 124 |
| `git` | 123 |
| `config` | 120 |
| `support` | 113 |
| `administrator` | 111 |
| `postgres` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 1009 |
| `123` | 616 |
| `1234` | 497 |
| `12345678` | 393 |
| `admin` | 388 |
| `12345` | 331 |
| `1` | 288 |
| `P@ssw0rd` | 242 |
| `admin123` | 238 |
| `password` | 174 |
| `123456789` | 146 |
| `000000` | 141 |
| `1111` | 140 |

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
| `INFO` | 724 |
| `PING` | 558 |
| `canary_env` | 453 |


_Generated from first-party honeypot capture. CC BY 4.0._
