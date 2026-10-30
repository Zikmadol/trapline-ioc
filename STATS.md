# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3889 attackers** · **750,931 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 207 |
| Used a planted canary credential | 54 |
| Seen on more than one sensor | 277 |
| Stage-2 hosts named in payloads | 52 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4903 |
| `ssh-exploit` | 1335 |
| `ssh-bruteforce` | 1106 |
| `redis-exploit` | 675 |
| `mcp-abuse` | 264 |
| `litellm-key-replay` | 92 |
| `llamacpp-abuse` | 88 |
| `ollama-abuse` | 77 |
| `docker-abuse` | 51 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2529 |
| `redis` | 694 |
| `mcp` | 404 |
| `llamacpp` | 267 |
| `litellm` | 184 |
| `vllm` | 172 |
| `jupyter` | 171 |
| `docker` | 132 |
| `ollama` | 130 |
| `hfhub` | 126 |
| `php` | 63 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1572 |
| `345gs5662d34` | 1086 |
| `admin` | 737 |
| `ubuntu` | 360 |
| `user` | 185 |
| `ftpuser` | 182 |
| `test` | 140 |
| `guest` | 117 |
| `git` | 114 |
| `deploy` | 112 |
| `postgres` | 109 |
| `administrator` | 98 |
| `ftp` | 93 |
| `oracle` | 83 |
| `debian` | 77 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1084 |
| `3245gs5662d34` | 1076 |
| `123456` | 876 |
| `123` | 563 |
| `1234` | 408 |
| `12345678` | 323 |
| `admin` | 286 |
| `1` | 257 |
| `12345` | 256 |
| `P@ssw0rd` | 187 |
| `admin123` | 177 |
| `password` | 157 |
| `123456789` | 127 |
| `000000` | 125 |
| `!QAZ2wsx` | 109 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1453 |
| `cd` | 1262 |
| `cat` | 1260 |
| `echo` | 1248 |
| `crontab` | 1222 |
| `lscpu` | 1220 |
| `ls` | 1115 |
| `free` | 1113 |
| `df` | 1110 |
| `top` | 1110 |
| `w` | 1109 |
| `whoami` | 1109 |
| `INFO` | 458 |
| `canary_env` | 340 |
| `PING` | 326 |


_Generated from first-party honeypot capture. CC BY 4.0._
