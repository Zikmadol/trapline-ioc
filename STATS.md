# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3113 attackers** · **613,755 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 36 |
| Seen on more than one sensor | 222 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2946 |
| `ssh-exploit` | 1203 |
| `ssh-bruteforce` | 709 |
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
| `ssh` | 1989 |
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
| `root` | 1148 |
| `345gs5662d34` | 963 |
| `admin` | 666 |
| `ubuntu` | 315 |
| `user` | 161 |
| `ftpuser` | 159 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 99 |
| `administrator` | 93 |
| `oracle` | 74 |
| `ftp` | 73 |
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 961 |
| `3245gs5662d34` | 954 |
| `123456` | 780 |
| `123` | 508 |
| `1234` | 369 |
| `12345678` | 285 |
| `admin` | 245 |
| `12345` | 232 |
| `1` | 228 |
| `P@ssw0rd` | 168 |
| `password` | 156 |
| `admin123` | 151 |
| `000000` | 118 |
| `123456789` | 115 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1313 |
| `cd` | 1131 |
| `cat` | 1130 |
| `echo` | 1115 |
| `crontab` | 1093 |
| `lscpu` | 1091 |
| `ls` | 990 |
| `free` | 989 |
| `df` | 987 |
| `top` | 987 |
| `whoami` | 986 |
| `w` | 985 |
| `INFO` | 387 |
| `canary_env` | 295 |
| `PING` | 263 |


_Generated from first-party honeypot capture. CC BY 4.0._
