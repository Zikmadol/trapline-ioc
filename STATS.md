# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6245 attackers** · **1,362,358 hostile actions** · covering 74 day(s) through 2026-11-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 342 |
| Used a planted canary credential | 269 |
| Seen on more than one sensor | 512 |
| Stage-2 hosts named in payloads | 73 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13585 |
| `ssh-bruteforce` | 1944 |
| `ssh-exploit` | 1467 |
| `redis-exploit` | 1131 |
| `mcp-abuse` | 349 |
| `docker-abuse` | 221 |
| `llamacpp-abuse` | 217 |
| `litellm-key-replay` | 203 |
| `ollama-abuse` | 169 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 32 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3575 |
| `redis` | 1163 |
| `mcp` | 689 |
| `llamacpp` | 612 |
| `vllm` | 481 |
| `litellm` | 425 |
| `docker` | 372 |
| `jupyter` | 324 |
| `ollama` | 301 |
| `hfhub` | 263 |
| `php` | 196 |
| `ray` | 68 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1934 |
| `345gs5662d34` | 1107 |
| `admin` | 954 |
| `ubuntu` | 440 |
| `guest` | 240 |
| `ftpuser` | 233 |
| `user` | 220 |
| `test` | 174 |
| `ftp` | 148 |
| `config` | 133 |
| `deploy` | 129 |
| `git` | 125 |
| `administrator` | 117 |
| `bin` | 117 |
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
| `12345678` | 409 |
| `12345` | 355 |
| `1` | 304 |
| `admin123` | 261 |
| `P@ssw0rd` | 255 |
| `password` | 174 |
| `1111` | 152 |
| `123456789` | 151 |
| `000000` | 147 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1604 |
| `cat` | 1375 |
| `cd` | 1370 |
| `echo` | 1343 |
| `crontab` | 1310 |
| `lscpu` | 1303 |
| `ls` | 1192 |
| `free` | 1186 |
| `whoami` | 1186 |
| `df` | 1183 |
| `top` | 1182 |
| `w` | 1182 |
| `INFO` | 799 |
| `PING` | 621 |
| `canary_env` | 584 |


_Generated from first-party honeypot capture. CC BY 4.0._
