# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3076 attackers** · **612,097 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 186 |
| Used a planted canary credential | 35 |
| Seen on more than one sensor | 216 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2872 |
| `ssh-exploit` | 1197 |
| `ssh-bruteforce` | 697 |
| `redis-exploit` | 564 |
| `mcp-abuse` | 235 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 59 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 38 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1970 |
| `redis` | 579 |
| `mcp` | 342 |
| `llamacpp` | 220 |
| `jupyter` | 134 |
| `vllm` | 130 |
| `litellm` | 123 |
| `ollama` | 101 |
| `hfhub` | 99 |
| `docker` | 92 |
| `ray` | 22 |
| `php` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1141 |
| `345gs5662d34` | 959 |
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
| `345gs5662d34` | 957 |
| `3245gs5662d34` | 950 |
| `123456` | 773 |
| `123` | 507 |
| `1234` | 368 |
| `12345678` | 282 |
| `admin` | 241 |
| `12345` | 231 |
| `1` | 227 |
| `P@ssw0rd` | 167 |
| `password` | 157 |
| `admin123` | 149 |
| `000000` | 118 |
| `123456789` | 115 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1307 |
| `cd` | 1126 |
| `cat` | 1125 |
| `echo` | 1111 |
| `crontab` | 1089 |
| `lscpu` | 1087 |
| `ls` | 986 |
| `free` | 985 |
| `df` | 983 |
| `top` | 983 |
| `whoami` | 982 |
| `w` | 981 |
| `INFO` | 381 |
| `canary_env` | 290 |
| `PING` | 261 |


_Generated from first-party honeypot capture. CC BY 4.0._
