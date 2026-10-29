# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3727 attackers** · **724,220 hostile actions** · covering 47 day(s) through 2026-10-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 199 |
| Used a planted canary credential | 51 |
| Seen on more than one sensor | 265 |
| Stage-2 hosts named in payloads | 47 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4472 |
| `ssh-exploit` | 1294 |
| `ssh-bruteforce` | 1070 |
| `redis-exploit` | 644 |
| `mcp-abuse` | 258 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 73 |
| `litellm-key-replay` | 65 |
| `docker-abuse` | 47 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2449 |
| `redis` | 662 |
| `mcp` | 389 |
| `llamacpp` | 255 |
| `vllm` | 163 |
| `jupyter` | 163 |
| `litellm` | 151 |
| `ollama` | 122 |
| `docker` | 122 |
| `hfhub` | 120 |
| `php` | 59 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1518 |
| `345gs5662d34` | 1045 |
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
| `345gs5662d34` | 1043 |
| `3245gs5662d34` | 1035 |
| `123456` | 860 |
| `123` | 524 |
| `1234` | 398 |
| `12345678` | 313 |
| `admin` | 277 |
| `12345` | 252 |
| `1` | 250 |
| `P@ssw0rd` | 183 |
| `admin123` | 170 |
| `password` | 150 |
| `123456789` | 125 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1410 |
| `cd` | 1219 |
| `cat` | 1218 |
| `echo` | 1205 |
| `crontab` | 1179 |
| `lscpu` | 1177 |
| `ls` | 1074 |
| `free` | 1072 |
| `df` | 1069 |
| `top` | 1069 |
| `w` | 1068 |
| `whoami` | 1068 |
| `INFO` | 439 |
| `canary_env` | 328 |
| `PING` | 310 |


_Generated from first-party honeypot capture. CC BY 4.0._
