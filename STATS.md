# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3801 attackers** · **737,202 hostile actions** · covering 47 day(s) through 2026-10-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 204 |
| Used a planted canary credential | 51 |
| Seen on more than one sensor | 273 |
| Stage-2 hosts named in payloads | 48 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4710 |
| `ssh-exploit` | 1301 |
| `ssh-bruteforce` | 1101 |
| `redis-exploit` | 663 |
| `mcp-abuse` | 263 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 77 |
| `litellm-key-replay` | 67 |
| `docker-abuse` | 49 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2490 |
| `redis` | 682 |
| `mcp` | 395 |
| `llamacpp` | 261 |
| `vllm` | 168 |
| `jupyter` | 166 |
| `litellm` | 157 |
| `ollama` | 128 |
| `docker` | 128 |
| `hfhub` | 124 |
| `php` | 60 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1550 |
| `345gs5662d34` | 1051 |
| `admin` | 730 |
| `ubuntu` | 355 |
| `user` | 178 |
| `ftpuser` | 177 |
| `test` | 140 |
| `guest` | 115 |
| `git` | 112 |
| `deploy` | 112 |
| `postgres` | 109 |
| `administrator` | 97 |
| `ftp` | 91 |
| `oracle` | 83 |
| `debian` | 74 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1049 |
| `3245gs5662d34` | 1041 |
| `123456` | 863 |
| `123` | 526 |
| `1234` | 400 |
| `12345678` | 318 |
| `admin` | 279 |
| `12345` | 253 |
| `1` | 251 |
| `P@ssw0rd` | 184 |
| `admin123` | 171 |
| `password` | 152 |
| `123456789` | 125 |
| `000000` | 124 |
| `!QAZ2wsx` | 108 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1419 |
| `cd` | 1227 |
| `cat` | 1226 |
| `echo` | 1213 |
| `crontab` | 1187 |
| `lscpu` | 1185 |
| `ls` | 1081 |
| `free` | 1079 |
| `df` | 1076 |
| `top` | 1076 |
| `w` | 1075 |
| `whoami` | 1075 |
| `INFO` | 449 |
| `canary_env` | 336 |
| `PING` | 319 |


_Generated from first-party honeypot capture. CC BY 4.0._
