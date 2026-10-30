# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3816 attackers** · **738,749 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 204 |
| Used a planted canary credential | 52 |
| Seen on more than one sensor | 273 |
| Stage-2 hosts named in payloads | 49 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4733 |
| `ssh-exploit` | 1315 |
| `ssh-bruteforce` | 1099 |
| `redis-exploit` | 663 |
| `mcp-abuse` | 264 |
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
| `ssh` | 2502 |
| `redis` | 682 |
| `mcp` | 397 |
| `llamacpp` | 261 |
| `vllm` | 168 |
| `jupyter` | 166 |
| `litellm` | 157 |
| `ollama` | 128 |
| `docker` | 128 |
| `hfhub` | 124 |
| `php` | 60 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1560 |
| `345gs5662d34` | 1066 |
| `admin` | 732 |
| `ubuntu` | 360 |
| `ftpuser` | 178 |
| `user` | 178 |
| `test` | 140 |
| `guest` | 116 |
| `git` | 112 |
| `deploy` | 112 |
| `postgres` | 109 |
| `administrator` | 97 |
| `ftp` | 92 |
| `oracle` | 83 |
| `debian` | 76 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1064 |
| `3245gs5662d34` | 1056 |
| `123456` | 867 |
| `123` | 543 |
| `1234` | 401 |
| `12345678` | 320 |
| `admin` | 280 |
| `1` | 256 |
| `12345` | 254 |
| `P@ssw0rd` | 185 |
| `admin123` | 172 |
| `password` | 156 |
| `123456789` | 125 |
| `000000` | 124 |
| `!QAZ2wsx` | 108 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1434 |
| `cd` | 1242 |
| `cat` | 1241 |
| `echo` | 1228 |
| `crontab` | 1202 |
| `lscpu` | 1200 |
| `ls` | 1096 |
| `free` | 1094 |
| `df` | 1091 |
| `top` | 1091 |
| `w` | 1090 |
| `whoami` | 1090 |
| `INFO` | 449 |
| `canary_env` | 337 |
| `PING` | 319 |


_Generated from first-party honeypot capture. CC BY 4.0._
