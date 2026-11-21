# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5865 attackers** · **1,281,183 hostile actions** · covering 70 day(s) through 2026-11-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 322 |
| Used a planted canary credential | 246 |
| Seen on more than one sensor | 487 |
| Stage-2 hosts named in payloads | 68 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13508 |
| `ssh-bruteforce` | 1889 |
| `ssh-exploit` | 1457 |
| `redis-exploit` | 1050 |
| `mcp-abuse` | 328 |
| `docker-abuse` | 191 |
| `litellm-key-replay` | 186 |
| `ollama-abuse` | 159 |
| `llamacpp-abuse` | 135 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 26 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3499 |
| `redis` | 1082 |
| `mcp` | 570 |
| `llamacpp` | 468 |
| `litellm` | 360 |
| `vllm` | 359 |
| `docker` | 328 |
| `jupyter` | 294 |
| `ollama` | 283 |
| `hfhub` | 239 |
| `php` | 172 |
| `ray` | 56 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1900 |
| `345gs5662d34` | 1105 |
| `admin` | 930 |
| `ubuntu` | 430 |
| `guest` | 231 |
| `ftpuser` | 225 |
| `user` | 218 |
| `test` | 174 |
| `ftp` | 139 |
| `deploy` | 127 |
| `git` | 125 |
| `config` | 124 |
| `postgres` | 114 |
| `support` | 114 |
| `administrator` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1102 |
| `3245gs5662d34` | 1094 |
| `123456` | 1021 |
| `123` | 627 |
| `1234` | 508 |
| `12345678` | 400 |
| `admin` | 397 |
| `12345` | 341 |
| `1` | 293 |
| `admin123` | 248 |
| `P@ssw0rd` | 246 |
| `password` | 171 |
| `123456789` | 148 |
| `1111` | 143 |
| `000000` | 142 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1584 |
| `cat` | 1362 |
| `cd` | 1357 |
| `echo` | 1334 |
| `crontab` | 1300 |
| `lscpu` | 1294 |
| `ls` | 1185 |
| `free` | 1179 |
| `whoami` | 1179 |
| `df` | 1176 |
| `top` | 1175 |
| `w` | 1175 |
| `INFO` | 742 |
| `PING` | 572 |
| `canary_env` | 459 |


_Generated from first-party honeypot capture. CC BY 4.0._
