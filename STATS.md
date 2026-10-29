# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3792 attackers** · **736,451 hostile actions** · covering 47 day(s) through 2026-10-29

| signal | count |
|---|---|
| GPU / AI-hardware probing | 203 |
| Used a planted canary credential | 51 |
| Seen on more than one sensor | 272 |
| Stage-2 hosts named in payloads | 48 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4664 |
| `ssh-exploit` | 1298 |
| `ssh-bruteforce` | 1100 |
| `redis-exploit` | 659 |
| `mcp-abuse` | 262 |
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
| `ssh` | 2486 |
| `redis` | 678 |
| `mcp` | 394 |
| `llamacpp` | 261 |
| `vllm` | 168 |
| `jupyter` | 166 |
| `litellm` | 157 |
| `ollama` | 128 |
| `docker` | 127 |
| `hfhub` | 124 |
| `php` | 60 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1548 |
| `345gs5662d34` | 1050 |
| `admin` | 729 |
| `ubuntu` | 353 |
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
| `345gs5662d34` | 1048 |
| `3245gs5662d34` | 1040 |
| `123456` | 862 |
| `123` | 524 |
| `1234` | 399 |
| `12345678` | 316 |
| `admin` | 279 |
| `12345` | 253 |
| `1` | 250 |
| `P@ssw0rd` | 184 |
| `admin123` | 171 |
| `password` | 152 |
| `123456789` | 125 |
| `000000` | 124 |
| `!QAZ2wsx` | 107 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1417 |
| `cd` | 1225 |
| `cat` | 1224 |
| `echo` | 1212 |
| `crontab` | 1186 |
| `lscpu` | 1184 |
| `ls` | 1080 |
| `free` | 1078 |
| `df` | 1075 |
| `top` | 1075 |
| `w` | 1074 |
| `whoami` | 1074 |
| `INFO` | 445 |
| `canary_env` | 335 |
| `PING` | 318 |


_Generated from first-party honeypot capture. CC BY 4.0._
