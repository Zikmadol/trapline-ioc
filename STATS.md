# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4032 attackers** · **799,838 hostile actions** · covering 51 day(s) through 2026-11-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 211 |
| Used a planted canary credential | 68 |
| Seen on more than one sensor | 296 |
| Stage-2 hosts named in payloads | 55 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5621 |
| `ssh-exploit` | 1357 |
| `ssh-bruteforce` | 1131 |
| `redis-exploit` | 700 |
| `mcp-abuse` | 269 |
| `litellm-key-replay` | 112 |
| `llamacpp-abuse` | 92 |
| `ollama-abuse` | 84 |
| `docker-abuse` | 55 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 16 |
| `vllm-key-replay` | 15 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2583 |
| `redis` | 719 |
| `mcp` | 418 |
| `llamacpp` | 293 |
| `litellm` | 210 |
| `vllm` | 183 |
| `jupyter` | 177 |
| `ollama` | 141 |
| `docker` | 138 |
| `hfhub` | 136 |
| `php` | 75 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1601 |
| `345gs5662d34` | 1098 |
| `admin` | 767 |
| `ubuntu` | 388 |
| `user` | 188 |
| `ftpuser` | 186 |
| `test` | 146 |
| `guest` | 124 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 109 |
| `administrator` | 100 |
| `ftp` | 99 |
| `oracle` | 86 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 900 |
| `123` | 586 |
| `1234` | 416 |
| `12345678` | 336 |
| `admin` | 300 |
| `1` | 264 |
| `12345` | 262 |
| `P@ssw0rd` | 194 |
| `admin123` | 188 |
| `password` | 157 |
| `123456789` | 132 |
| `000000` | 126 |
| `!QAZ2wsx` | 111 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1479 |
| `cd` | 1282 |
| `cat` | 1280 |
| `echo` | 1261 |
| `crontab` | 1236 |
| `lscpu` | 1233 |
| `ls` | 1128 |
| `free` | 1126 |
| `whoami` | 1124 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 474 |
| `canary_env` | 351 |
| `PING` | 338 |


_Generated from first-party honeypot capture. CC BY 4.0._
