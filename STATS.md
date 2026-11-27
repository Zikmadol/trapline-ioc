# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6441 attackers** · **1,394,996 hostile actions** · covering 76 day(s) through 2026-11-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 347 |
| Used a planted canary credential | 276 |
| Seen on more than one sensor | 527 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13604 |
| `ssh-bruteforce` | 1994 |
| `ssh-exploit` | 1475 |
| `redis-exploit` | 1193 |
| `mcp-abuse` | 364 |
| `docker-abuse` | 231 |
| `llamacpp-abuse` | 225 |
| `litellm-key-replay` | 223 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3637 |
| `redis` | 1225 |
| `mcp` | 716 |
| `llamacpp` | 632 |
| `vllm` | 501 |
| `litellm` | 452 |
| `docker` | 388 |
| `jupyter` | 338 |
| `ollama` | 310 |
| `hfhub` | 268 |
| `php` | 205 |
| `ray` | 78 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1980 |
| `345gs5662d34` | 1107 |
| `admin` | 966 |
| `ubuntu` | 442 |
| `guest` | 245 |
| `ftpuser` | 239 |
| `user` | 226 |
| `test` | 175 |
| `ftp` | 153 |
| `config` | 138 |
| `deploy` | 132 |
| `git` | 126 |
| `bin` | 121 |
| `administrator` | 119 |
| `george` | 119 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1097 |
| `123456` | 1052 |
| `123` | 642 |
| `1234` | 542 |
| `admin` | 423 |
| `12345678` | 416 |
| `12345` | 360 |
| `1` | 303 |
| `admin123` | 268 |
| `P@ssw0rd` | 259 |
| `password` | 175 |
| `1111` | 155 |
| `123456789` | 152 |
| `000000` | 149 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1624 |
| `cat` | 1393 |
| `cd` | 1388 |
| `echo` | 1360 |
| `crontab` | 1328 |
| `lscpu` | 1320 |
| `ls` | 1209 |
| `free` | 1203 |
| `whoami` | 1203 |
| `df` | 1200 |
| `top` | 1199 |
| `w` | 1199 |
| `INFO` | 853 |
| `PING` | 677 |
| `canary_env` | 602 |


_Generated from first-party honeypot capture. CC BY 4.0._
