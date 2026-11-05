# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4243 attackers** · **871,754 hostile actions** · covering 54 day(s) through 2026-11-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 218 |
| Used a planted canary credential | 129 |
| Seen on more than one sensor | 317 |
| Stage-2 hosts named in payloads | 57 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6455 |
| `ssh-exploit` | 1374 |
| `ssh-bruteforce` | 1153 |
| `redis-exploit` | 747 |
| `mcp-abuse` | 277 |
| `litellm-key-replay` | 130 |
| `ollama-abuse` | 99 |
| `llamacpp-abuse` | 98 |
| `docker-abuse` | 59 |
| `jupyter-abuse` | 39 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2628 |
| `redis` | 771 |
| `mcp` | 445 |
| `llamacpp` | 322 |
| `litellm` | 245 |
| `vllm` | 200 |
| `jupyter` | 198 |
| `ollama` | 167 |
| `hfhub` | 157 |
| `docker` | 153 |
| `php` | 92 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1620 |
| `345gs5662d34` | 1098 |
| `admin` | 787 |
| `ubuntu` | 401 |
| `user` | 194 |
| `ftpuser` | 192 |
| `test` | 150 |
| `guest` | 133 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `ftp` | 104 |
| `administrator` | 102 |
| `oracle` | 90 |
| `AdminGPON` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 913 |
| `123` | 592 |
| `1234` | 422 |
| `12345678` | 345 |
| `admin` | 310 |
| `1` | 267 |
| `12345` | 267 |
| `P@ssw0rd` | 200 |
| `admin123` | 195 |
| `password` | 159 |
| `123456789` | 133 |
| `000000` | 129 |
| `!QAZ2wsx` | 113 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1492 |
| `cd` | 1291 |
| `cat` | 1289 |
| `echo` | 1266 |
| `crontab` | 1240 |
| `lscpu` | 1237 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 512 |
| `PING` | 369 |
| `canary_env` | 368 |


_Generated from first-party honeypot capture. CC BY 4.0._
