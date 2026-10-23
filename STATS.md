# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3068 attackers** · **611,635 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 186 |
| Used a planted canary credential | 35 |
| Seen on more than one sensor | 214 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2856 |
| `ssh-exploit` | 1195 |
| `ssh-bruteforce` | 691 |
| `redis-exploit` | 564 |
| `mcp-abuse` | 235 |
| `llamacpp-abuse` | 80 |
| `ollama-abuse` | 60 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 38 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1961 |
| `redis` | 579 |
| `mcp` | 342 |
| `llamacpp` | 219 |
| `jupyter` | 134 |
| `vllm` | 130 |
| `litellm` | 123 |
| `ollama` | 101 |
| `hfhub` | 99 |
| `docker` | 92 |
| `ray` | 22 |
| `php` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1133 |
| `345gs5662d34` | 957 |
| `admin` | 661 |
| `ubuntu` | 313 |
| `user` | 161 |
| `ftpuser` | 158 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 98 |
| `administrator` | 93 |
| `oracle` | 74 |
| `ftp` | 72 |
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 955 |
| `3245gs5662d34` | 948 |
| `123456` | 771 |
| `123` | 507 |
| `1234` | 368 |
| `12345678` | 282 |
| `admin` | 241 |
| `12345` | 231 |
| `1` | 227 |
| `P@ssw0rd` | 167 |
| `password` | 157 |
| `admin123` | 148 |
| `000000` | 118 |
| `123456789` | 115 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1305 |
| `cd` | 1124 |
| `cat` | 1123 |
| `echo` | 1109 |
| `crontab` | 1087 |
| `lscpu` | 1085 |
| `ls` | 984 |
| `free` | 983 |
| `df` | 981 |
| `top` | 981 |
| `whoami` | 980 |
| `w` | 979 |
| `INFO` | 381 |
| `canary_env` | 290 |
| `PING` | 261 |


_Generated from first-party honeypot capture. CC BY 4.0._
