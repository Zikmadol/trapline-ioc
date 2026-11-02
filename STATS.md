# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4073 attackers** · **816,624 hostile actions** · covering 51 day(s) through 2026-11-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 212 |
| Used a planted canary credential | 81 |
| Seen on more than one sensor | 299 |
| Stage-2 hosts named in payloads | 55 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5800 |
| `ssh-exploit` | 1360 |
| `ssh-bruteforce` | 1134 |
| `redis-exploit` | 708 |
| `mcp-abuse` | 270 |
| `litellm-key-replay` | 119 |
| `llamacpp-abuse` | 92 |
| `ollama-abuse` | 87 |
| `docker-abuse` | 56 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 16 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2589 |
| `redis` | 727 |
| `mcp` | 422 |
| `llamacpp` | 294 |
| `litellm` | 220 |
| `vllm` | 185 |
| `jupyter` | 178 |
| `ollama` | 146 |
| `docker` | 140 |
| `hfhub` | 139 |
| `php` | 78 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1605 |
| `345gs5662d34` | 1098 |
| `admin` | 770 |
| `ubuntu` | 389 |
| `user` | 189 |
| `ftpuser` | 187 |
| `test` | 147 |
| `guest` | 126 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `administrator` | 101 |
| `ftp` | 100 |
| `oracle` | 87 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 901 |
| `123` | 587 |
| `1234` | 417 |
| `12345678` | 337 |
| `admin` | 302 |
| `1` | 264 |
| `12345` | 263 |
| `P@ssw0rd` | 196 |
| `admin123` | 189 |
| `password` | 157 |
| `123456789` | 132 |
| `000000` | 127 |
| `!QAZ2wsx` | 112 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1480 |
| `cd` | 1282 |
| `cat` | 1280 |
| `echo` | 1262 |
| `crontab` | 1237 |
| `lscpu` | 1234 |
| `ls` | 1128 |
| `free` | 1126 |
| `whoami` | 1125 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 481 |
| `canary_env` | 353 |
| `PING` | 344 |


_Generated from first-party honeypot capture. CC BY 4.0._
