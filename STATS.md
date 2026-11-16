# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5355 attackers** · **1,189,715 hostile actions** · covering 65 day(s) through 2026-11-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 300 |
| Used a planted canary credential | 195 |
| Seen on more than one sensor | 449 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10912 |
| `ssh-bruteforce` | 1637 |
| `ssh-exploit` | 1404 |
| `redis-exploit` | 987 |
| `mcp-abuse` | 306 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 163 |
| `ollama-abuse` | 148 |
| `llamacpp-abuse` | 126 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 25 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3184 |
| `redis` | 1019 |
| `mcp` | 527 |
| `llamacpp` | 424 |
| `litellm` | 332 |
| `vllm` | 325 |
| `docker` | 290 |
| `jupyter` | 274 |
| `ollama` | 261 |
| `hfhub` | 217 |
| `php` | 156 |
| `ray` | 47 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1748 |
| `345gs5662d34` | 1098 |
| `admin` | 890 |
| `ubuntu` | 415 |
| `ftpuser` | 215 |
| `user` | 212 |
| `guest` | 204 |
| `test` | 169 |
| `ftp` | 129 |
| `git` | 119 |
| `deploy` | 116 |
| `postgres` | 111 |
| `administrator` | 106 |
| `config` | 104 |
| `support` | 100 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 965 |
| `123` | 604 |
| `1234` | 468 |
| `12345678` | 385 |
| `admin` | 370 |
| `12345` | 298 |
| `1` | 278 |
| `admin123` | 233 |
| `P@ssw0rd` | 225 |
| `password` | 174 |
| `123456789` | 143 |
| `000000` | 136 |
| `1111` | 128 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1516 |
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
| `INFO` | 704 |
| `PING` | 538 |
| `canary_env` | 431 |


_Generated from first-party honeypot capture. CC BY 4.0._
