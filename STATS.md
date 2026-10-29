# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3755 attackers** · **728,213 hostile actions** · covering 47 day(s) through 2026-10-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 200 |
| Used a planted canary credential | 51 |
| Seen on more than one sensor | 267 |
| Stage-2 hosts named in payloads | 47 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4532 |
| `ssh-exploit` | 1293 |
| `ssh-bruteforce` | 1081 |
| `redis-exploit` | 653 |
| `mcp-abuse` | 262 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 75 |
| `litellm-key-replay` | 67 |
| `docker-abuse` | 48 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2460 |
| `redis` | 672 |
| `mcp` | 393 |
| `llamacpp` | 256 |
| `vllm` | 165 |
| `jupyter` | 164 |
| `litellm` | 154 |
| `ollama` | 124 |
| `docker` | 123 |
| `hfhub` | 121 |
| `php` | 60 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1527 |
| `345gs5662d34` | 1046 |
| `admin` | 727 |
| `ubuntu` | 350 |
| `ftpuser` | 176 |
| `user` | 176 |
| `test` | 140 |
| `guest` | 114 |
| `git` | 112 |
| `deploy` | 112 |
| `postgres` | 106 |
| `administrator` | 96 |
| `ftp` | 90 |
| `oracle` | 82 |
| `debian` | 74 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1044 |
| `3245gs5662d34` | 1036 |
| `123456` | 861 |
| `123` | 524 |
| `1234` | 398 |
| `12345678` | 313 |
| `admin` | 278 |
| `12345` | 252 |
| `1` | 250 |
| `P@ssw0rd` | 183 |
| `admin123` | 170 |
| `password` | 151 |
| `123456789` | 125 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1411 |
| `cd` | 1220 |
| `cat` | 1219 |
| `echo` | 1206 |
| `crontab` | 1180 |
| `lscpu` | 1178 |
| `ls` | 1075 |
| `free` | 1073 |
| `df` | 1070 |
| `top` | 1070 |
| `w` | 1069 |
| `whoami` | 1069 |
| `INFO` | 442 |
| `canary_env` | 333 |
| `PING` | 316 |


_Generated from first-party honeypot capture. CC BY 4.0._
