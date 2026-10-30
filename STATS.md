# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3827 attackers** · **740,157 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 205 |
| Used a planted canary credential | 52 |
| Seen on more than one sensor | 273 |
| Stage-2 hosts named in payloads | 51 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4773 |
| `ssh-exploit` | 1319 |
| `ssh-bruteforce` | 1099 |
| `redis-exploit` | 666 |
| `mcp-abuse` | 264 |
| `llamacpp-abuse` | 86 |
| `ollama-abuse` | 77 |
| `litellm-key-replay` | 68 |
| `docker-abuse` | 50 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2506 |
| `redis` | 685 |
| `mcp` | 398 |
| `llamacpp` | 261 |
| `vllm` | 168 |
| `jupyter` | 166 |
| `litellm` | 158 |
| `docker` | 129 |
| `ollama` | 128 |
| `hfhub` | 124 |
| `php` | 61 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1561 |
| `345gs5662d34` | 1069 |
| `admin` | 734 |
| `ubuntu` | 360 |
| `user` | 180 |
| `ftpuser` | 178 |
| `test` | 140 |
| `guest` | 116 |
| `deploy` | 113 |
| `git` | 112 |
| `postgres` | 109 |
| `administrator` | 97 |
| `ftp` | 92 |
| `oracle` | 83 |
| `debian` | 76 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1067 |
| `3245gs5662d34` | 1059 |
| `123456` | 868 |
| `123` | 547 |
| `1234` | 402 |
| `12345678` | 321 |
| `admin` | 281 |
| `1` | 257 |
| `12345` | 255 |
| `P@ssw0rd` | 185 |
| `admin123` | 174 |
| `password` | 156 |
| `123456789` | 126 |
| `000000` | 124 |
| `!QAZ2wsx` | 108 |

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
