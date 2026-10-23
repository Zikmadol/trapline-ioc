# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3123 attackers** · **615,718 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 36 |
| Seen on more than one sensor | 222 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2974 |
| `ssh-exploit` | 1206 |
| `ssh-bruteforce` | 716 |
| `redis-exploit` | 575 |
| `mcp-abuse` | 237 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 59 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 33 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1999 |
| `redis` | 590 |
| `mcp` | 346 |
| `llamacpp` | 225 |
| `jupyter` | 136 |
| `vllm` | 133 |
| `litellm` | 124 |
| `ollama` | 102 |
| `hfhub` | 101 |
| `docker` | 95 |
| `php` | 23 |
| `ray` | 22 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1157 |
| `345gs5662d34` | 965 |
| `admin` | 667 |
| `ubuntu` | 315 |
| `user` | 162 |
| `ftpuser` | 160 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 100 |
| `administrator` | 93 |
| `oracle` | 75 |
| `ftp` | 74 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 963 |
| `3245gs5662d34` | 956 |
| `123456` | 781 |
| `123` | 508 |
| `1234` | 370 |
| `12345678` | 285 |
| `admin` | 245 |
| `12345` | 232 |
| `1` | 228 |
| `P@ssw0rd` | 168 |
| `password` | 156 |
| `admin123` | 154 |
| `000000` | 118 |
| `123456789` | 116 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1315 |
| `cd` | 1133 |
| `cat` | 1132 |
| `echo` | 1117 |
| `crontab` | 1095 |
| `lscpu` | 1093 |
| `ls` | 992 |
| `free` | 991 |
| `df` | 989 |
| `top` | 989 |
| `whoami` | 988 |
| `w` | 987 |
| `INFO` | 387 |
| `canary_env` | 295 |
| `PING` | 263 |


_Generated from first-party honeypot capture. CC BY 4.0._
