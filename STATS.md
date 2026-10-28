# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3591 attackers** · **706,212 hostile actions** · covering 46 day(s) through 2026-10-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 195 |
| Used a planted canary credential | 41 |
| Seen on more than one sensor | 262 |
| Stage-2 hosts named in payloads | 45 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3919 |
| `ssh-exploit` | 1267 |
| `ssh-bruteforce` | 1000 |
| `redis-exploit` | 635 |
| `mcp-abuse` | 253 |
| `llamacpp-abuse` | 84 |
| `ollama-abuse` | 71 |
| `litellm-key-replay` | 63 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2351 |
| `redis` | 652 |
| `mcp` | 377 |
| `llamacpp` | 247 |
| `jupyter` | 159 |
| `vllm` | 154 |
| `litellm` | 144 |
| `docker` | 117 |
| `ollama` | 116 |
| `hfhub` | 113 |
| `php` | 56 |
| `ray` | 29 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1448 |
| `345gs5662d34` | 1021 |
| `admin` | 713 |
| `ubuntu` | 346 |
| `ftpuser` | 173 |
| `user` | 173 |
| `test` | 139 |
| `deploy` | 112 |
| `guest` | 111 |
| `git` | 111 |
| `postgres` | 106 |
| `administrator` | 96 |
| `ftp` | 86 |
| `oracle` | 77 |
| `AdminGPON` | 71 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1019 |
| `3245gs5662d34` | 1011 |
| `123456` | 831 |
| `123` | 520 |
| `1234` | 394 |
| `12345678` | 310 |
| `admin` | 271 |
| `1` | 248 |
| `12345` | 246 |
| `P@ssw0rd` | 181 |
| `admin123` | 166 |
| `password` | 152 |
| `123456789` | 124 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1384 |
| `cd` | 1194 |
| `cat` | 1193 |
| `echo` | 1180 |
| `crontab` | 1154 |
| `lscpu` | 1152 |
| `ls` | 1049 |
| `free` | 1047 |
| `df` | 1044 |
| `top` | 1044 |
| `w` | 1043 |
| `whoami` | 1043 |
| `INFO` | 428 |
| `canary_env` | 319 |
| `PING` | 302 |


_Generated from first-party honeypot capture. CC BY 4.0._
