# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3705 attackers** · **722,983 hostile actions** · covering 47 day(s) through 2026-10-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 198 |
| Used a planted canary credential | 51 |
| Seen on more than one sensor | 265 |
| Stage-2 hosts named in payloads | 47 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4378 |
| `ssh-exploit` | 1292 |
| `ssh-bruteforce` | 1056 |
| `redis-exploit` | 643 |
| `mcp-abuse` | 256 |
| `llamacpp-abuse` | 85 |
| `ollama-abuse` | 73 |
| `litellm-key-replay` | 65 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 36 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2433 |
| `redis` | 661 |
| `mcp` | 386 |
| `llamacpp` | 253 |
| `jupyter` | 162 |
| `vllm` | 160 |
| `litellm` | 151 |
| `ollama` | 122 |
| `docker` | 121 |
| `hfhub` | 119 |
| `php` | 59 |
| `ray` | 30 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1504 |
| `345gs5662d34` | 1043 |
| `admin` | 724 |
| `ubuntu` | 349 |
| `user` | 176 |
| `ftpuser` | 175 |
| `test` | 140 |
| `guest` | 113 |
| `git` | 112 |
| `deploy` | 112 |
| `postgres` | 106 |
| `administrator` | 96 |
| `ftp` | 89 |
| `oracle` | 79 |
| `dev` | 73 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1041 |
| `3245gs5662d34` | 1033 |
| `123456` | 857 |
| `123` | 524 |
| `1234` | 397 |
| `12345678` | 313 |
| `admin` | 275 |
| `12345` | 251 |
| `1` | 250 |
| `P@ssw0rd` | 182 |
| `admin123` | 169 |
| `password` | 151 |
| `123456789` | 125 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1408 |
| `cd` | 1217 |
| `cat` | 1216 |
| `echo` | 1203 |
| `crontab` | 1177 |
| `lscpu` | 1175 |
| `ls` | 1072 |
| `free` | 1070 |
| `df` | 1067 |
| `top` | 1067 |
| `w` | 1066 |
| `whoami` | 1066 |
| `INFO` | 438 |
| `canary_env` | 325 |
| `PING` | 309 |


_Generated from first-party honeypot capture. CC BY 4.0._
