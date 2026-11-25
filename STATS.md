# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6191 attackers** · **1,347,375 hostile actions** · covering 74 day(s) through 2026-11-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 340 |
| Used a planted canary credential | 263 |
| Seen on more than one sensor | 510 |
| Stage-2 hosts named in payloads | 73 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13559 |
| `ssh-bruteforce` | 1930 |
| `ssh-exploit` | 1464 |
| `redis-exploit` | 1119 |
| `mcp-abuse` | 349 |
| `docker-abuse` | 220 |
| `llamacpp-abuse` | 203 |
| `litellm-key-replay` | 201 |
| `ollama-abuse` | 168 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 32 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3557 |
| `redis` | 1151 |
| `mcp` | 675 |
| `llamacpp` | 596 |
| `vllm` | 466 |
| `litellm` | 419 |
| `docker` | 370 |
| `jupyter` | 322 |
| `ollama` | 299 |
| `hfhub` | 262 |
| `php` | 195 |
| `ray` | 68 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1918 |
| `345gs5662d34` | 1106 |
| `admin` | 953 |
| `ubuntu` | 438 |
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
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1041 |
| `123` | 633 |
| `1234` | 524 |
| `admin` | 418 |
| `12345678` | 411 |
| `12345` | 354 |
| `1` | 302 |
| `admin123` | 261 |
| `P@ssw0rd` | 255 |
| `password` | 174 |
| `1111` | 153 |
| `123456789` | 152 |
| `000000` | 145 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1600 |
| `cat` | 1372 |
| `cd` | 1367 |
| `echo` | 1339 |
| `crontab` | 1306 |
| `lscpu` | 1299 |
| `ls` | 1189 |
| `free` | 1183 |
| `whoami` | 1183 |
| `df` | 1180 |
| `top` | 1179 |
| `w` | 1179 |
| `INFO` | 789 |
| `PING` | 614 |
| `canary_env` | 571 |


_Generated from first-party honeypot capture. CC BY 4.0._
