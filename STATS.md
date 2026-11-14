# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5052 attackers** · **1,154,509 hostile actions** · covering 63 day(s) through 2026-11-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 292 |
| Used a planted canary credential | 179 |
| Seen on more than one sensor | 434 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10023 |
| `ssh-bruteforce` | 1427 |
| `ssh-exploit` | 1402 |
| `redis-exploit` | 957 |
| `mcp-abuse` | 303 |
| `litellm-key-replay` | 165 |
| `docker-abuse` | 153 |
| `ollama-abuse` | 141 |
| `llamacpp-abuse` | 118 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 24 |
| `php-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2964 |
| `redis` | 988 |
| `mcp` | 519 |
| `llamacpp` | 403 |
| `litellm` | 312 |
| `vllm` | 307 |
| `docker` | 276 |
| `jupyter` | 260 |
| `ollama` | 244 |
| `hfhub` | 209 |
| `php` | 148 |
| `ray` | 46 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1711 |
| `345gs5662d34` | 1098 |
| `admin` | 867 |
| `ubuntu` | 414 |
| `ftpuser` | 210 |
| `user` | 203 |
| `guest` | 164 |
| `test` | 164 |
| `ftp` | 123 |
| `git` | 118 |
| `deploy` | 116 |
| `postgres` | 109 |
| `administrator` | 106 |
| `config` | 93 |
| `AdminGPON` | 91 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 953 |
| `123` | 602 |
| `1234` | 460 |
| `12345678` | 378 |
| `admin` | 353 |
| `12345` | 291 |
| `1` | 272 |
| `admin123` | 228 |
| `P@ssw0rd` | 221 |
| `password` | 167 |
| `123456789` | 141 |
| `000000` | 132 |
| `!QAZ2wsx` | 125 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1514 |
| `cat` | 1303 |
| `cd` | 1299 |
| `echo` | 1276 |
| `crontab` | 1245 |
| `lscpu` | 1242 |
| `ls` | 1131 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1124 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 684 |
| `PING` | 523 |
| `canary_env` | 418 |


_Generated from first-party honeypot capture. CC BY 4.0._
