# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5018 attackers** · **1,143,427 hostile actions** · covering 63 day(s) through 2026-11-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 292 |
| Used a planted canary credential | 179 |
| Seen on more than one sensor | 434 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 9938 |
| `ssh-bruteforce` | 1402 |
| `ssh-exploit` | 1400 |
| `redis-exploit` | 955 |
| `mcp-abuse` | 303 |
| `litellm-key-replay` | 165 |
| `docker-abuse` | 151 |
| `ollama-abuse` | 138 |
| `llamacpp-abuse` | 118 |
| `jupyter-abuse` | 49 |
| `vllm-abuse` | 24 |
| `php-abuse` | 23 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2937 |
| `redis` | 986 |
| `mcp` | 518 |
| `llamacpp` | 402 |
| `litellm` | 311 |
| `vllm` | 307 |
| `docker` | 274 |
| `jupyter` | 258 |
| `ollama` | 241 |
| `hfhub` | 209 |
| `php` | 148 |
| `ray` | 46 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1706 |
| `345gs5662d34` | 1098 |
| `admin` | 863 |
| `ubuntu` | 414 |
| `ftpuser` | 210 |
| `user` | 199 |
| `test` | 164 |
| `guest` | 162 |
| `ftp` | 123 |
| `git` | 118 |
| `deploy` | 116 |
| `postgres` | 109 |
| `administrator` | 106 |
| `config` | 91 |
| `oracle` | 91 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 953 |
| `123` | 601 |
| `1234` | 458 |
| `12345678` | 378 |
| `admin` | 353 |
| `12345` | 291 |
| `1` | 273 |
| `admin123` | 226 |
| `P@ssw0rd` | 221 |
| `password` | 167 |
| `123456789` | 139 |
| `000000` | 133 |
| `!QAZ2wsx` | 125 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1514 |
| `cat` | 1302 |
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
| `INFO` | 682 |
| `PING` | 521 |
| `canary_env` | 418 |


_Generated from first-party honeypot capture. CC BY 4.0._
