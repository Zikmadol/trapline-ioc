# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5870 attackers** · **1,281,618 hostile actions** · covering 70 day(s) through 2026-11-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 322 |
| Used a planted canary credential | 246 |
| Seen on more than one sensor | 488 |
| Stage-2 hosts named in payloads | 68 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13508 |
| `ssh-bruteforce` | 1889 |
| `ssh-exploit` | 1458 |
| `redis-exploit` | 1052 |
| `mcp-abuse` | 328 |
| `docker-abuse` | 191 |
| `litellm-key-replay` | 186 |
| `ollama-abuse` | 160 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 26 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3500 |
| `redis` | 1084 |
| `mcp` | 570 |
| `llamacpp` | 472 |
| `litellm` | 360 |
| `vllm` | 359 |
| `docker` | 328 |
| `jupyter` | 295 |
| `ollama` | 285 |
| `hfhub` | 239 |
| `php` | 173 |
| `ray` | 56 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1900 |
| `345gs5662d34` | 1105 |
| `admin` | 930 |
| `ubuntu` | 430 |
| `guest` | 231 |
| `ftpuser` | 224 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 139 |
| `deploy` | 127 |
| `git` | 125 |
| `config` | 124 |
| `administrator` | 114 |
| `postgres` | 114 |
| `support` | 114 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1102 |
| `3245gs5662d34` | 1094 |
| `123456` | 1023 |
| `123` | 627 |
| `1234` | 508 |
| `12345678` | 400 |
| `admin` | 397 |
| `12345` | 341 |
| `1` | 294 |
| `admin123` | 248 |
| `P@ssw0rd` | 246 |
| `password` | 171 |
| `123456789` | 148 |
| `000000` | 143 |
| `1111` | 143 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1585 |
| `cat` | 1363 |
| `cd` | 1358 |
| `echo` | 1335 |
| `crontab` | 1301 |
| `lscpu` | 1295 |
| `ls` | 1186 |
| `free` | 1180 |
| `whoami` | 1180 |
| `df` | 1177 |
| `top` | 1176 |
| `w` | 1176 |
| `INFO` | 743 |
| `PING` | 572 |
| `canary_env` | 459 |


_Generated from first-party honeypot capture. CC BY 4.0._
