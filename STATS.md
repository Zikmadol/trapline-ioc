# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3467 attackers** · **683,905 hostile actions** · covering 45 day(s) through 2026-10-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 193 |
| Used a planted canary credential | 40 |
| Seen on more than one sensor | 256 |
| Stage-2 hosts named in payloads | 44 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3563 |
| `ssh-exploit` | 1247 |
| `ssh-bruteforce` | 927 |
| `redis-exploit` | 619 |
| `mcp-abuse` | 249 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 68 |
| `litellm-key-replay` | 60 |
| `docker-abuse` | 45 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2255 |
| `redis` | 635 |
| `mcp` | 369 |
| `llamacpp` | 240 |
| `jupyter` | 155 |
| `vllm` | 147 |
| `litellm` | 139 |
| `ollama` | 113 |
| `docker` | 111 |
| `hfhub` | 110 |
| `php` | 50 |
| `ray` | 27 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1386 |
| `345gs5662d34` | 1003 |
| `admin` | 699 |
| `ubuntu` | 336 |
| `ftpuser` | 169 |
| `user` | 169 |
| `test` | 138 |
| `deploy` | 112 |
| `git` | 111 |
| `guest` | 109 |
| `postgres` | 103 |
| `administrator` | 95 |
| `ftp` | 82 |
| `oracle` | 76 |
| `dev` | 70 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1001 |
| `3245gs5662d34` | 993 |
| `123456` | 818 |
| `123` | 514 |
| `1234` | 388 |
| `12345678` | 305 |
| `admin` | 269 |
| `12345` | 243 |
| `1` | 242 |
| `P@ssw0rd` | 179 |
| `admin123` | 164 |
| `password` | 152 |
| `123456789` | 122 |
| `000000` | 122 |
| `!QAZ2wsx` | 104 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1364 |
| `cd` | 1174 |
| `cat` | 1173 |
| `echo` | 1158 |
| `crontab` | 1134 |
| `lscpu` | 1132 |
| `ls` | 1029 |
| `free` | 1028 |
| `df` | 1026 |
| `top` | 1026 |
| `whoami` | 1025 |
| `w` | 1024 |
| `INFO` | 416 |
| `canary_env` | 314 |
| `PING` | 291 |


_Generated from first-party honeypot capture. CC BY 4.0._
