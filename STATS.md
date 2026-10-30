# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3837 attackers** · **745,522 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 206 |
| Used a planted canary credential | 52 |
| Seen on more than one sensor | 274 |
| Stage-2 hosts named in payloads | 51 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4794 |
| `ssh-exploit` | 1320 |
| `ssh-bruteforce` | 1100 |
| `redis-exploit` | 666 |
| `mcp-abuse` | 264 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 77 |
| `litellm-key-replay` | 76 |
| `docker-abuse` | 50 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2508 |
| `redis` | 685 |
| `mcp` | 398 |
| `llamacpp` | 261 |
| `vllm` | 168 |
| `litellm` | 166 |
| `jupyter` | 166 |
| `docker` | 129 |
| `ollama` | 128 |
| `hfhub` | 124 |
| `php` | 62 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1562 |
| `345gs5662d34` | 1069 |
| `admin` | 734 |
| `ubuntu` | 361 |
| `user` | 181 |
| `ftpuser` | 178 |
| `test` | 140 |
| `guest` | 116 |
| `git` | 112 |
| `deploy` | 112 |
| `postgres` | 109 |
| `administrator` | 98 |
| `ftp` | 92 |
| `oracle` | 83 |
| `debian` | 76 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1067 |
| `3245gs5662d34` | 1059 |
| `123456` | 868 |
| `123` | 546 |
| `1234` | 401 |
| `12345678` | 320 |
| `admin` | 281 |
| `1` | 257 |
| `12345` | 255 |
| `P@ssw0rd` | 185 |
| `admin123` | 174 |
| `password` | 156 |
| `123456789` | 125 |
| `000000` | 125 |
| `!QAZ2wsx` | 109 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1438 |
| `cd` | 1245 |
| `cat` | 1244 |
| `echo` | 1232 |
| `crontab` | 1206 |
| `lscpu` | 1204 |
| `ls` | 1099 |
| `free` | 1097 |
| `df` | 1094 |
| `top` | 1094 |
| `w` | 1093 |
| `whoami` | 1093 |
| `INFO` | 451 |
| `canary_env` | 337 |
| `PING` | 320 |


_Generated from first-party honeypot capture. CC BY 4.0._
