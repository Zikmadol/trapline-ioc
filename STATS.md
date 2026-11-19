# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5745 attackers** · **1,234,456 hostile actions** · covering 68 day(s) through 2026-11-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 316 |
| Used a planted canary credential | 238 |
| Seen on more than one sensor | 477 |
| Stage-2 hosts named in payloads | 65 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 12815 |
| `ssh-bruteforce` | 1847 |
| `ssh-exploit` | 1445 |
| `redis-exploit` | 1022 |
| `mcp-abuse` | 321 |
| `docker-abuse` | 184 |
| `litellm-key-replay` | 183 |
| `ollama-abuse` | 154 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3442 |
| `redis` | 1054 |
| `mcp` | 556 |
| `llamacpp` | 457 |
| `litellm` | 350 |
| `vllm` | 347 |
| `docker` | 317 |
| `jupyter` | 284 |
| `ollama` | 277 |
| `hfhub` | 233 |
| `php` | 166 |
| `ray` | 54 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1872 |
| `345gs5662d34` | 1104 |
| `admin` | 917 |
| `ubuntu` | 424 |
| `guest` | 226 |
| `ftpuser` | 221 |
| `user` | 218 |
| `test` | 175 |
| `ftp` | 135 |
| `deploy` | 124 |
| `git` | 123 |
| `config` | 120 |
| `support` | 113 |
| `postgres` | 112 |
| `administrator` | 111 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1101 |
| `3245gs5662d34` | 1093 |
| `123456` | 1007 |
| `123` | 616 |
| `1234` | 498 |
| `12345678` | 394 |
| `admin` | 389 |
| `12345` | 331 |
| `1` | 288 |
| `P@ssw0rd` | 242 |
| `admin123` | 238 |
| `password` | 175 |
| `123456789` | 146 |
| `000000` | 139 |
| `1111` | 138 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1569 |
| `cat` | 1348 |
| `cd` | 1342 |
| `echo` | 1323 |
| `crontab` | 1290 |
| `lscpu` | 1285 |
| `ls` | 1175 |
| `whoami` | 1170 |
| `free` | 1169 |
| `df` | 1167 |
| `top` | 1165 |
| `w` | 1165 |
| `INFO` | 720 |
| `PING` | 554 |
| `canary_env` | 451 |


_Generated from first-party honeypot capture. CC BY 4.0._
