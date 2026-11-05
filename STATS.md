# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4225 attackers** · **870,188 hostile actions** · covering 54 day(s) through 2026-11-05

| signal | count |
|---|---|
| GPU / AI-hardware probing | 218 |
| Used a planted canary credential | 129 |
| Seen on more than one sensor | 317 |
| Stage-2 hosts named in payloads | 57 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 6388 |
| `ssh-exploit` | 1369 |
| `ssh-bruteforce` | 1149 |
| `redis-exploit` | 744 |
| `mcp-abuse` | 276 |
| `litellm-key-replay` | 128 |
| `llamacpp-abuse` | 98 |
| `ollama-abuse` | 98 |
| `docker-abuse` | 57 |
| `jupyter-abuse` | 39 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2618 |
| `redis` | 767 |
| `mcp` | 443 |
| `llamacpp` | 320 |
| `litellm` | 242 |
| `vllm` | 198 |
| `jupyter` | 194 |
| `ollama` | 166 |
| `hfhub` | 156 |
| `docker` | 151 |
| `php` | 91 |
| `ray` | 37 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1616 |
| `345gs5662d34` | 1098 |
| `admin` | 784 |
| `ubuntu` | 398 |
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
| `123456` | 912 |
| `123` | 590 |
| `1234` | 422 |
| `12345678` | 343 |
| `admin` | 309 |
| `1` | 267 |
| `12345` | 267 |
| `P@ssw0rd` | 200 |
| `admin123` | 194 |
| `password` | 159 |
| `123456789` | 133 |
| `000000` | 129 |
| `!QAZ2wsx` | 113 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1487 |
| `cd` | 1286 |
| `cat` | 1284 |
| `echo` | 1266 |
| `crontab` | 1240 |
| `lscpu` | 1237 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 510 |
| `PING` | 367 |
| `canary_env` | 366 |


_Generated from first-party honeypot capture. CC BY 4.0._
