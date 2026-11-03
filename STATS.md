# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4080 attackers** · **817,446 hostile actions** · covering 52 day(s) through 2026-11-03

| signal | count |
|---|---|
| GPU / AI-hardware probing | 212 |
| Used a planted canary credential | 81 |
| Seen on more than one sensor | 300 |
| Stage-2 hosts named in payloads | 56 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5840 |
| `ssh-exploit` | 1360 |
| `ssh-bruteforce` | 1136 |
| `redis-exploit` | 711 |
| `mcp-abuse` | 270 |
| `litellm-key-replay` | 119 |
| `llamacpp-abuse` | 92 |
| `ollama-abuse` | 88 |
| `docker-abuse` | 56 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 16 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2591 |
| `redis` | 730 |
| `mcp` | 423 |
| `llamacpp` | 295 |
| `litellm` | 221 |
| `vllm` | 186 |
| `jupyter` | 180 |
| `ollama` | 148 |
| `docker` | 141 |
| `hfhub` | 140 |
| `php` | 78 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1607 |
| `345gs5662d34` | 1098 |
| `admin` | 771 |
| `ubuntu` | 390 |
| `user` | 190 |
| `ftpuser` | 187 |
| `test` | 148 |
| `guest` | 127 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `administrator` | 101 |
| `ftp` | 100 |
| `oracle` | 88 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 902 |
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
| `echo` | 1263 |
| `crontab` | 1237 |
| `lscpu` | 1234 |
| `ls` | 1128 |
| `free` | 1126 |
| `whoami` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 484 |
| `canary_env` | 353 |
| `PING` | 346 |


_Generated from first-party honeypot capture. CC BY 4.0._
