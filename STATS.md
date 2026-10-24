# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3182 attackers** · **642,179 hostile actions** · covering 42 day(s) through 2026-10-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 38 |
| Seen on more than one sensor | 229 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3095 |
| `ssh-exploit` | 1216 |
| `ssh-bruteforce` | 749 |
| `redis-exploit` | 581 |
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
| `ssh` | 2042 |
| `redis` | 596 |
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
| `root` | 1196 |
| `345gs5662d34` | 974 |
| `admin` | 673 |
| `ubuntu` | 318 |
| `ftpuser` | 162 |
| `user` | 161 |
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
| `345gs5662d34` | 972 |
| `3245gs5662d34` | 965 |
| `123456` | 783 |
| `123` | 509 |
| `1234` | 372 |
| `12345678` | 288 |
| `admin` | 248 |
| `1` | 232 |
| `12345` | 232 |
| `P@ssw0rd` | 169 |
| `password` | 156 |
| `admin123` | 154 |
| `000000` | 119 |
| `123456789` | 117 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1324 |
| `cd` | 1142 |
| `cat` | 1141 |
| `echo` | 1126 |
| `crontab` | 1104 |
| `lscpu` | 1102 |
| `ls` | 1001 |
| `free` | 1000 |
| `df` | 998 |
| `top` | 998 |
| `whoami` | 997 |
| `w` | 996 |
| `INFO` | 391 |
| `canary_env` | 298 |
| `PING` | 267 |


_Generated from first-party honeypot capture. CC BY 4.0._
