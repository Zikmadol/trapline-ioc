# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3781 attackers** · **735,812 hostile actions** · covering 47 day(s) through 2026-10-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 202 |
| Used a planted canary credential | 51 |
| Seen on more than one sensor | 269 |
| Stage-2 hosts named in payloads | 47 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4618 |
| `ssh-exploit` | 1296 |
| `ssh-bruteforce` | 1097 |
| `redis-exploit` | 656 |
| `mcp-abuse` | 262 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 77 |
| `litellm-key-replay` | 67 |
| `docker-abuse` | 49 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2480 |
| `redis` | 675 |
| `mcp` | 393 |
| `llamacpp` | 258 |
| `vllm` | 166 |
| `jupyter` | 165 |
| `litellm` | 156 |
| `ollama` | 128 |
| `docker` | 126 |
| `hfhub` | 122 |
| `php` | 60 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1543 |
| `345gs5662d34` | 1048 |
| `admin` | 729 |
| `ubuntu` | 350 |
| `ftpuser` | 177 |
| `user` | 176 |
| `test` | 140 |
| `guest` | 115 |
| `git` | 112 |
| `deploy` | 112 |
| `postgres` | 108 |
| `administrator` | 97 |
| `ftp` | 91 |
| `oracle` | 83 |
| `debian` | 74 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1046 |
| `3245gs5662d34` | 1038 |
| `123456` | 862 |
| `123` | 524 |
| `1234` | 399 |
| `12345678` | 314 |
| `admin` | 279 |
| `12345` | 253 |
| `1` | 250 |
| `P@ssw0rd` | 184 |
| `admin123` | 171 |
| `password` | 151 |
| `123456789` | 125 |
| `000000` | 124 |
| `!QAZ2wsx` | 107 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1414 |
| `cd` | 1222 |
| `cat` | 1221 |
| `echo` | 1209 |
| `crontab` | 1183 |
| `lscpu` | 1181 |
| `ls` | 1077 |
| `free` | 1075 |
| `df` | 1072 |
| `top` | 1072 |
| `w` | 1071 |
| `whoami` | 1071 |
| `INFO` | 444 |
| `canary_env` | 334 |
| `PING` | 318 |


_Generated from first-party honeypot capture. CC BY 4.0._
