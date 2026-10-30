# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3871 attackers** · **747,309 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 207 |
| Used a planted canary credential | 53 |
| Seen on more than one sensor | 275 |
| Stage-2 hosts named in payloads | 51 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4851 |
| `ssh-exploit` | 1328 |
| `ssh-bruteforce` | 1103 |
| `redis-exploit` | 670 |
| `mcp-abuse` | 265 |
| `litellm-key-replay` | 92 |
| `llamacpp-abuse` | 87 |
| `ollama-abuse` | 77 |
| `docker-abuse` | 51 |
| `jupyter-abuse` | 37 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2519 |
| `redis` | 689 |
| `mcp` | 399 |
| `llamacpp` | 263 |
| `litellm` | 184 |
| `vllm` | 170 |
| `jupyter` | 169 |
| `docker` | 131 |
| `ollama` | 128 |
| `hfhub` | 125 |
| `php` | 63 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1567 |
| `345gs5662d34` | 1077 |
| `admin` | 737 |
| `ubuntu` | 360 |
| `user` | 184 |
| `ftpuser` | 179 |
| `test` | 140 |
| `guest` | 117 |
| `git` | 114 |
| `deploy` | 112 |
| `postgres` | 109 |
| `administrator` | 98 |
| `ftp` | 93 |
| `oracle` | 83 |
| `debian` | 76 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1075 |
| `3245gs5662d34` | 1067 |
| `123456` | 874 |
| `123` | 554 |
| `1234` | 406 |
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
| `uname` | 1446 |
| `cd` | 1253 |
| `cat` | 1252 |
| `echo` | 1240 |
| `crontab` | 1214 |
| `lscpu` | 1212 |
| `ls` | 1107 |
| `free` | 1105 |
| `df` | 1102 |
| `top` | 1102 |
| `w` | 1101 |
| `whoami` | 1101 |
| `INFO` | 455 |
| `canary_env` | 338 |
| `PING` | 322 |


_Generated from first-party honeypot capture. CC BY 4.0._
