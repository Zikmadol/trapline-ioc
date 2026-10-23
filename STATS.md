# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3103 attackers** · **613,354 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 186 |
| Used a planted canary credential | 35 |
| Seen on more than one sensor | 221 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2936 |
| `ssh-exploit` | 1198 |
| `ssh-bruteforce` | 706 |
| `redis-exploit` | 574 |
| `mcp-abuse` | 237 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 59 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 33 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1981 |
| `redis` | 589 |
| `mcp` | 346 |
| `llamacpp` | 223 |
| `jupyter` | 136 |
| `vllm` | 132 |
| `litellm` | 124 |
| `ollama` | 102 |
| `hfhub` | 101 |
| `docker` | 93 |
| `ray` | 22 |
| `php` | 21 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1147 |
| `345gs5662d34` | 960 |
| `admin` | 664 |
| `ubuntu` | 313 |
| `user` | 161 |
| `ftpuser` | 159 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 99 |
| `administrator` | 93 |
| `oracle` | 74 |
| `ftp` | 73 |
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 958 |
| `3245gs5662d34` | 951 |
| `123456` | 775 |
| `123` | 507 |
| `1234` | 369 |
| `12345678` | 283 |
| `admin` | 244 |
| `12345` | 232 |
| `1` | 228 |
| `P@ssw0rd` | 168 |
| `password` | 156 |
| `admin123` | 150 |
| `000000` | 118 |
| `123456789` | 115 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1308 |
| `cd` | 1127 |
| `cat` | 1126 |
| `echo` | 1112 |
| `crontab` | 1090 |
| `lscpu` | 1088 |
| `ls` | 987 |
| `free` | 986 |
| `df` | 984 |
| `top` | 984 |
| `whoami` | 983 |
| `w` | 982 |
| `INFO` | 387 |
| `canary_env` | 295 |
| `PING` | 263 |


_Generated from first-party honeypot capture. CC BY 4.0._
