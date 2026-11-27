# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6456 attackers** · **1,395,258 hostile actions** · covering 76 day(s) through 2026-11-27

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
| `ssh-bruteforce` | 1999 |
| `ssh-exploit` | 1477 |
| `redis-exploit` | 1199 |
| `mcp-abuse` | 365 |
| `docker-abuse` | 231 |
| `llamacpp-abuse` | 225 |
| `litellm-key-replay` | 224 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3644 |
| `redis` | 1231 |
| `mcp` | 717 |
| `llamacpp` | 632 |
| `vllm` | 501 |
| `litellm` | 455 |
| `docker` | 389 |
| `jupyter` | 339 |
| `ollama` | 310 |
| `hfhub` | 269 |
| `php` | 206 |
| `ray` | 78 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1985 |
| `345gs5662d34` | 1107 |
| `admin` | 966 |
| `ubuntu` | 442 |
| `guest` | 245 |
| `ftpuser` | 239 |
| `user` | 227 |
| `test` | 177 |
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
| `123` | 643 |
| `1234` | 542 |
| `admin` | 424 |
| `12345678` | 416 |
| `12345` | 360 |
| `1` | 303 |
| `admin123` | 268 |
| `P@ssw0rd` | 260 |
| `password` | 176 |
| `1111` | 155 |
| `123456789` | 152 |
| `000000` | 149 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1626 |
| `cat` | 1395 |
| `cd` | 1390 |
| `echo` | 1362 |
| `crontab` | 1330 |
| `lscpu` | 1322 |
| `ls` | 1211 |
| `free` | 1205 |
| `whoami` | 1205 |
| `df` | 1202 |
| `top` | 1201 |
| `w` | 1201 |
| `INFO` | 857 |
| `PING` | 680 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
