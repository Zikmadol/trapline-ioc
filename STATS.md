# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3222 attackers** · **648,496 hostile actions** · covering 42 day(s) through 2026-10-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 189 |
| Used a planted canary credential | 38 |
| Seen on more than one sensor | 234 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3159 |
| `ssh-exploit` | 1226 |
| `ssh-bruteforce` | 772 |
| `redis-exploit` | 585 |
| `mcp-abuse` | 240 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 64 |
| `litellm-key-replay` | 55 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2075 |
| `redis` | 600 |
| `mcp` | 352 |
| `llamacpp` | 230 |
| `jupyter` | 140 |
| `vllm` | 136 |
| `litellm` | 128 |
| `ollama` | 106 |
| `hfhub` | 103 |
| `docker` | 98 |
| `php` | 30 |
| `ray` | 23 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1220 |
| `345gs5662d34` | 980 |
| `admin` | 677 |
| `ubuntu` | 322 |
| `ftpuser` | 163 |
| `user` | 162 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 108 |
| `postgres` | 104 |
| `guest` | 101 |
| `administrator` | 93 |
| `ftp` | 76 |
| `oracle` | 75 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 978 |
| `3245gs5662d34` | 971 |
| `123456` | 790 |
| `123` | 510 |
| `1234` | 375 |
| `12345678` | 290 |
| `admin` | 250 |
| `12345` | 236 |
| `1` | 232 |
| `P@ssw0rd` | 171 |
| `admin123` | 157 |
| `password` | 155 |
| `000000` | 119 |
| `123456789` | 118 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1334 |
| `cd` | 1150 |
| `cat` | 1149 |
| `echo` | 1134 |
| `crontab` | 1111 |
| `lscpu` | 1109 |
| `ls` | 1007 |
| `free` | 1006 |
| `df` | 1004 |
| `top` | 1004 |
| `whoami` | 1003 |
| `w` | 1002 |
| `INFO` | 393 |
| `canary_env` | 299 |
| `PING` | 269 |


_Generated from first-party honeypot capture. CC BY 4.0._
