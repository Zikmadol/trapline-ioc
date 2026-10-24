# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3191 attackers** · **646,914 hostile actions** · covering 42 day(s) through 2026-10-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 38 |
| Seen on more than one sensor | 229 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3113 |
| `ssh-exploit` | 1218 |
| `ssh-bruteforce` | 754 |
| `redis-exploit` | 583 |
| `mcp-abuse` | 239 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 63 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2049 |
| `redis` | 598 |
| `mcp` | 349 |
| `llamacpp` | 228 |
| `jupyter` | 140 |
| `vllm` | 135 |
| `litellm` | 126 |
| `ollama` | 105 |
| `hfhub` | 102 |
| `docker` | 96 |
| `php` | 30 |
| `ray` | 22 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1201 |
| `345gs5662d34` | 975 |
| `admin` | 673 |
| `ubuntu` | 319 |
| `ftpuser` | 162 |
| `user` | 162 |
| `test` | 132 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 100 |
| `administrator` | 93 |
| `ftp` | 75 |
| `oracle` | 75 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 973 |
| `3245gs5662d34` | 966 |
| `123456` | 785 |
| `123` | 509 |
| `1234` | 372 |
| `12345678` | 288 |
| `admin` | 248 |
| `12345` | 232 |
| `1` | 231 |
| `P@ssw0rd` | 169 |
| `password` | 157 |
| `admin123` | 154 |
| `000000` | 119 |
| `123456789` | 117 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1325 |
| `cd` | 1143 |
| `cat` | 1142 |
| `echo` | 1127 |
| `crontab` | 1105 |
| `lscpu` | 1103 |
| `ls` | 1002 |
| `free` | 1001 |
| `df` | 999 |
| `top` | 999 |
| `whoami` | 998 |
| `w` | 997 |
| `INFO` | 392 |
| `canary_env` | 298 |
| `PING` | 268 |


_Generated from first-party honeypot capture. CC BY 4.0._
