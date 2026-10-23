# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3067 attackers** · **611,546 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 186 |
| Used a planted canary credential | 35 |
| Seen on more than one sensor | 214 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2849 |
| `ssh-exploit` | 1194 |
| `ssh-bruteforce` | 692 |
| `redis-exploit` | 564 |
| `mcp-abuse` | 235 |
| `llamacpp-abuse` | 79 |
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
| `mcp` | 341 |
| `llamacpp` | 218 |
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
| `345gs5662d34` | 956 |
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
| `oracle` | 73 |
| `ftp` | 71 |
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 954 |
| `3245gs5662d34` | 947 |
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
| `uname` | 1304 |
| `cd` | 1123 |
| `cat` | 1122 |
| `echo` | 1108 |
| `crontab` | 1086 |
| `lscpu` | 1084 |
| `ls` | 983 |
| `free` | 982 |
| `df` | 980 |
| `top` | 980 |
| `whoami` | 979 |
| `w` | 978 |
| `INFO` | 381 |
| `canary_env` | 289 |
| `PING` | 261 |


_Generated from first-party honeypot capture. CC BY 4.0._
