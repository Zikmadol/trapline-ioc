# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3550 attackers** · **697,121 hostile actions** · covering 45 day(s) through 2026-10-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 194 |
| Used a planted canary credential | 40 |
| Seen on more than one sensor | 258 |
| Stage-2 hosts named in payloads | 45 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3692 |
| `ssh-exploit` | 1263 |
| `ssh-bruteforce` | 979 |
| `redis-exploit` | 627 |
| `mcp-abuse` | 250 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 70 |
| `litellm-key-replay` | 61 |
| `docker-abuse` | 45 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2323 |
| `redis` | 643 |
| `mcp` | 372 |
| `llamacpp` | 240 |
| `jupyter` | 158 |
| `vllm` | 151 |
| `litellm` | 141 |
| `ollama` | 115 |
| `docker` | 114 |
| `hfhub` | 111 |
| `php` | 51 |
| `ray` | 27 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1428 |
| `345gs5662d34` | 1018 |
| `admin` | 703 |
| `ubuntu` | 341 |
| `user` | 174 |
| `ftpuser` | 171 |
| `test` | 138 |
| `deploy` | 112 |
| `git` | 111 |
| `guest` | 110 |
| `postgres` | 105 |
| `administrator` | 96 |
| `ftp` | 84 |
| `oracle` | 76 |
| `AdminGPON` | 70 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1016 |
| `3245gs5662d34` | 1008 |
| `123456` | 826 |
| `123` | 520 |
| `1234` | 393 |
| `12345678` | 306 |
| `admin` | 270 |
| `1` | 248 |
| `12345` | 245 |
| `P@ssw0rd` | 180 |
| `admin123` | 164 |
| `password` | 151 |
| `123456789` | 123 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1381 |
| `cd` | 1190 |
| `cat` | 1189 |
| `echo` | 1175 |
| `crontab` | 1150 |
| `lscpu` | 1149 |
| `ls` | 1045 |
| `free` | 1043 |
| `df` | 1041 |
| `top` | 1041 |
| `w` | 1040 |
| `whoami` | 1040 |
| `INFO` | 422 |
| `canary_env` | 315 |
| `PING` | 297 |


_Generated from first-party honeypot capture. CC BY 4.0._
