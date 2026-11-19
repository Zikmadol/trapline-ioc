# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5736 attackers** · **1,231,106 hostile actions** · covering 68 day(s) through 2026-11-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 315 |
| Used a planted canary credential | 238 |
| Seen on more than one sensor | 477 |
| Stage-2 hosts named in payloads | 65 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 12739 |
| `ssh-bruteforce` | 1841 |
| `ssh-exploit` | 1442 |
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
| `ssh` | 3433 |
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
| `root` | 1864 |
| `345gs5662d34` | 1103 |
| `admin` | 916 |
| `ubuntu` | 425 |
| `guest` | 226 |
| `ftpuser` | 221 |
| `user` | 218 |
| `test` | 174 |
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
| `345gs5662d34` | 1100 |
| `3245gs5662d34` | 1092 |
| `123456` | 1006 |
| `123` | 615 |
| `1234` | 496 |
| `12345678` | 393 |
| `admin` | 389 |
| `12345` | 329 |
| `1` | 286 |
| `P@ssw0rd` | 242 |
| `admin123` | 238 |
| `password` | 175 |
| `123456789` | 146 |
| `000000` | 139 |
| `1111` | 135 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1566 |
| `cat` | 1346 |
| `cd` | 1340 |
| `echo` | 1320 |
| `crontab` | 1287 |
| `lscpu` | 1282 |
| `ls` | 1173 |
| `whoami` | 1168 |
| `free` | 1167 |
| `df` | 1165 |
| `top` | 1163 |
| `w` | 1163 |
| `INFO` | 720 |
| `PING` | 554 |
| `canary_env` | 451 |


_Generated from first-party honeypot capture. CC BY 4.0._
