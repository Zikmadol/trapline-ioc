# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3204 attackers** · **648,077 hostile actions** · covering 42 day(s) through 2026-10-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 38 |
| Seen on more than one sensor | 230 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3137 |
| `ssh-exploit` | 1223 |
| `ssh-bruteforce` | 760 |
| `redis-exploit` | 584 |
| `mcp-abuse` | 239 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 63 |
| `litellm-key-replay` | 55 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2060 |
| `redis` | 599 |
| `mcp` | 350 |
| `llamacpp` | 228 |
| `jupyter` | 140 |
| `vllm` | 136 |
| `litellm` | 127 |
| `ollama` | 105 |
| `hfhub` | 102 |
| `docker` | 97 |
| `php` | 30 |
| `ray` | 22 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1208 |
| `345gs5662d34` | 978 |
| `admin` | 676 |
| `ubuntu` | 321 |
| `ftpuser` | 163 |
| `user` | 162 |
| `test` | 132 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 101 |
| `administrator` | 93 |
| `ftp` | 76 |
| `oracle` | 75 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 976 |
| `3245gs5662d34` | 969 |
| `123456` | 788 |
| `123` | 510 |
| `1234` | 374 |
| `12345678` | 290 |
| `admin` | 249 |
| `12345` | 234 |
| `1` | 232 |
| `P@ssw0rd` | 171 |
| `password` | 156 |
| `admin123` | 156 |
| `000000` | 119 |
| `123456789` | 118 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1331 |
| `cd` | 1148 |
| `cat` | 1147 |
| `echo` | 1130 |
| `crontab` | 1108 |
| `lscpu` | 1106 |
| `ls` | 1005 |
| `free` | 1004 |
| `df` | 1002 |
| `top` | 1002 |
| `whoami` | 1001 |
| `w` | 1000 |
| `INFO` | 393 |
| `canary_env` | 298 |
| `PING` | 269 |


_Generated from first-party honeypot capture. CC BY 4.0._
