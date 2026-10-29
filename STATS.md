# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3715 attackers** · **723,987 hostile actions** · covering 47 day(s) through 2026-10-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 198 |
| Used a planted canary credential | 51 |
| Seen on more than one sensor | 265 |
| Stage-2 hosts named in payloads | 47 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4459 |
| `ssh-exploit` | 1292 |
| `ssh-bruteforce` | 1062 |
| `redis-exploit` | 644 |
| `mcp-abuse` | 257 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 73 |
| `litellm-key-replay` | 65 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2439 |
| `redis` | 662 |
| `mcp` | 388 |
| `llamacpp` | 254 |
| `vllm` | 163 |
| `jupyter` | 163 |
| `litellm` | 151 |
| `ollama` | 122 |
| `docker` | 121 |
| `hfhub` | 120 |
| `php` | 59 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1508 |
| `345gs5662d34` | 1043 |
| `admin` | 726 |
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
| `dev` | 73 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1041 |
| `3245gs5662d34` | 1033 |
| `123456` | 858 |
| `123` | 524 |
| `1234` | 398 |
| `12345678` | 313 |
| `admin` | 277 |
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
| `INFO` | 439 |
| `canary_env` | 327 |
| `PING` | 310 |


_Generated from first-party honeypot capture. CC BY 4.0._
