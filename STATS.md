# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3649 attackers** · **720,476 hostile actions** · covering 46 day(s) through 2026-10-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 196 |
| Used a planted canary credential | 43 |
| Seen on more than one sensor | 265 |
| Stage-2 hosts named in payloads | 46 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4292 |
| `ssh-exploit` | 1281 |
| `ssh-bruteforce` | 1023 |
| `redis-exploit` | 642 |
| `mcp-abuse` | 256 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 73 |
| `litellm-key-replay` | 63 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 36 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2389 |
| `redis` | 660 |
| `mcp` | 385 |
| `llamacpp` | 252 |
| `jupyter` | 162 |
| `vllm` | 160 |
| `litellm` | 148 |
| `ollama` | 121 |
| `docker` | 121 |
| `hfhub` | 119 |
| `php` | 59 |
| `ray` | 30 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1469 |
| `345gs5662d34` | 1036 |
| `admin` | 720 |
| `ubuntu` | 348 |
| `ftpuser` | 175 |
| `user` | 174 |
| `test` | 140 |
| `guest` | 112 |
| `deploy` | 112 |
| `git` | 111 |
| `postgres` | 106 |
| `administrator` | 96 |
| `ftp` | 88 |
| `oracle` | 78 |
| `AdminGPON` | 71 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1034 |
| `3245gs5662d34` | 1026 |
| `123456` | 849 |
| `123` | 520 |
| `1234` | 396 |
| `12345678` | 312 |
| `admin` | 276 |
| `1` | 249 |
| `12345` | 249 |
| `P@ssw0rd` | 182 |
| `admin123` | 169 |
| `password` | 152 |
| `123456789` | 125 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1401 |
| `cd` | 1210 |
| `cat` | 1209 |
| `echo` | 1196 |
| `crontab` | 1170 |
| `lscpu` | 1168 |
| `ls` | 1065 |
| `free` | 1063 |
| `df` | 1060 |
| `top` | 1060 |
| `w` | 1059 |
| `whoami` | 1059 |
| `INFO` | 436 |
| `canary_env` | 325 |
| `PING` | 308 |


_Generated from first-party honeypot capture. CC BY 4.0._
