# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5413 attackers** · **1,193,408 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 301 |
| Used a planted canary credential | 198 |
| Seen on more than one sensor | 453 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10980 |
| `ssh-bruteforce` | 1676 |
| `ssh-exploit` | 1413 |
| `redis-exploit` | 991 |
| `mcp-abuse` | 308 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 162 |
| `ollama-abuse` | 149 |
| `llamacpp-abuse` | 127 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 25 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3233 |
| `redis` | 1023 |
| `mcp` | 534 |
| `llamacpp` | 428 |
| `litellm` | 334 |
| `vllm` | 326 |
| `docker` | 291 |
| `jupyter` | 276 |
| `ollama` | 263 |
| `hfhub` | 220 |
| `php` | 158 |
| `ray` | 48 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1778 |
| `345gs5662d34` | 1100 |
| `admin` | 895 |
| `ubuntu` | 420 |
| `ftpuser` | 215 |
| `user` | 214 |
| `guest` | 209 |
| `test` | 173 |
| `ftp` | 129 |
| `git` | 120 |
| `deploy` | 117 |
| `postgres` | 111 |
| `config` | 108 |
| `administrator` | 106 |
| `support` | 105 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1098 |
| `3245gs5662d34` | 1090 |
| `123456` | 974 |
| `123` | 608 |
| `1234` | 468 |
| `12345678` | 385 |
| `admin` | 370 |
| `12345` | 298 |
| `1` | 278 |
| `admin123` | 233 |
| `P@ssw0rd` | 232 |
| `password` | 174 |
| `123456789` | 144 |
| `000000` | 136 |
| `1111` | 128 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1529 |
| `cat` | 1313 |
| `cd` | 1307 |
| `echo` | 1286 |
| `crontab` | 1253 |
| `lscpu` | 1250 |
| `ls` | 1141 |
| `whoami` | 1136 |
| `free` | 1134 |
| `df` | 1132 |
| `top` | 1131 |
| `w` | 1131 |
| `INFO` | 707 |
| `PING` | 540 |
| `canary_env` | 433 |


_Generated from first-party honeypot capture. CC BY 4.0._
