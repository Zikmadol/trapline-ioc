# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6230 attackers** · **1,359,021 hostile actions** · covering 74 day(s) through 2026-11-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 340 |
| Used a planted canary credential | 268 |
| Seen on more than one sensor | 511 |
| Stage-2 hosts named in payloads | 73 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13582 |
| `ssh-bruteforce` | 1936 |
| `ssh-exploit` | 1467 |
| `redis-exploit` | 1128 |
| `mcp-abuse` | 349 |
| `docker-abuse` | 220 |
| `llamacpp-abuse` | 216 |
| `litellm-key-replay` | 202 |
| `ollama-abuse` | 169 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 32 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3566 |
| `redis` | 1160 |
| `mcp` | 687 |
| `llamacpp` | 611 |
| `vllm` | 479 |
| `litellm` | 424 |
| `docker` | 370 |
| `jupyter` | 323 |
| `ollama` | 300 |
| `hfhub` | 262 |
| `php` | 196 |
| `ray` | 68 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1926 |
| `345gs5662d34` | 1107 |
| `admin` | 953 |
| `ubuntu` | 440 |
| `guest` | 240 |
| `ftpuser` | 233 |
| `user` | 220 |
| `test` | 174 |
| `ftp` | 148 |
| `config` | 133 |
| `deploy` | 129 |
| `git` | 125 |
| `bin` | 117 |
| `administrator` | 116 |
| `george` | 115 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1096 |
| `123456` | 1041 |
| `123` | 634 |
| `1234` | 527 |
| `admin` | 417 |
| `12345678` | 410 |
| `12345` | 355 |
| `1` | 303 |
| `admin123` | 260 |
| `P@ssw0rd` | 255 |
| `password` | 175 |
| `123456789` | 152 |
| `1111` | 152 |
| `000000` | 146 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1603 |
| `cat` | 1375 |
| `cd` | 1370 |
| `echo` | 1342 |
| `crontab` | 1309 |
| `lscpu` | 1302 |
| `ls` | 1192 |
| `free` | 1186 |
| `whoami` | 1186 |
| `df` | 1183 |
| `top` | 1182 |
| `w` | 1182 |
| `INFO` | 796 |
| `PING` | 619 |
| `canary_env` | 583 |


_Generated from first-party honeypot capture. CC BY 4.0._
