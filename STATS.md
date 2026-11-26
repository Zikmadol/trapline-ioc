# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6338 attackers** · **1,377,583 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 343 |
| Used a planted canary credential | 271 |
| Seen on more than one sensor | 516 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13587 |
| `ssh-bruteforce` | 1962 |
| `ssh-exploit` | 1472 |
| `redis-exploit` | 1156 |
| `mcp-abuse` | 361 |
| `llamacpp-abuse` | 225 |
| `docker-abuse` | 223 |
| `litellm-key-replay` | 210 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 34 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3600 |
| `redis` | 1188 |
| `mcp` | 710 |
| `llamacpp` | 625 |
| `vllm` | 495 |
| `litellm` | 436 |
| `docker` | 375 |
| `jupyter` | 333 |
| `ollama` | 308 |
| `hfhub` | 265 |
| `php` | 200 |
| `ray` | 76 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1954 |
| `345gs5662d34` | 1107 |
| `admin` | 958 |
| `ubuntu` | 442 |
| `guest` | 242 |
| `ftpuser` | 236 |
| `user` | 223 |
| `test` | 175 |
| `ftp` | 150 |
| `config` | 135 |
| `deploy` | 131 |
| `git` | 126 |
| `bin` | 119 |
| `administrator` | 117 |
| `george` | 117 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1096 |
| `123456` | 1047 |
| `123` | 637 |
| `1234` | 535 |
| `admin` | 420 |
| `12345678` | 412 |
| `12345` | 358 |
| `1` | 302 |
| `admin123` | 265 |
| `P@ssw0rd` | 257 |
| `password` | 173 |
| `1111` | 153 |
| `123456789` | 152 |
| `000000` | 147 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1615 |
| `cat` | 1385 |
| `cd` | 1380 |
| `echo` | 1353 |
| `crontab` | 1320 |
| `lscpu` | 1313 |
| `ls` | 1202 |
| `free` | 1196 |
| `whoami` | 1196 |
| `df` | 1193 |
| `top` | 1192 |
| `w` | 1192 |
| `INFO` | 818 |
| `PING` | 640 |
| `canary_env` | 597 |


_Generated from first-party honeypot capture. CC BY 4.0._
