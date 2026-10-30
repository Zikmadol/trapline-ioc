# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3880 attackers** · **748,005 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 207 |
| Used a planted canary credential | 53 |
| Seen on more than one sensor | 276 |
| Stage-2 hosts named in payloads | 52 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4872 |
| `ssh-exploit` | 1334 |
| `ssh-bruteforce` | 1105 |
| `redis-exploit` | 670 |
| `mcp-abuse` | 264 |
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
| `ssh` | 2527 |
| `redis` | 689 |
| `mcp` | 399 |
| `llamacpp` | 265 |
| `litellm` | 184 |
| `vllm` | 171 |
| `jupyter` | 170 |
| `docker` | 131 |
| `ollama` | 130 |
| `hfhub` | 125 |
| `php` | 63 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1572 |
| `345gs5662d34` | 1085 |
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
| `345gs5662d34` | 1083 |
| `3245gs5662d34` | 1075 |
| `123456` | 874 |
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
| `uname` | 1452 |
| `cd` | 1261 |
| `cat` | 1259 |
| `echo` | 1247 |
| `crontab` | 1221 |
| `lscpu` | 1219 |
| `ls` | 1114 |
| `free` | 1112 |
| `df` | 1109 |
| `top` | 1109 |
| `w` | 1108 |
| `whoami` | 1108 |
| `INFO` | 455 |
| `canary_env` | 338 |
| `PING` | 322 |


_Generated from first-party honeypot capture. CC BY 4.0._
