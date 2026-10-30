# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3899 attackers** · **754,708 hostile actions** · covering 48 day(s) through 2026-10-30

| signal | count |
|---|---|
| GPU / AI-hardware probing | 207 |
| Used a planted canary credential | 54 |
| Seen on more than one sensor | 278 |
| Stage-2 hosts named in payloads | 52 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 4925 |
| `ssh-exploit` | 1346 |
| `ssh-bruteforce` | 1104 |
| `redis-exploit` | 675 |
| `mcp-abuse` | 264 |
| `litellm-key-replay` | 92 |
| `llamacpp-abuse` | 88 |
| `ollama-abuse` | 77 |
| `docker-abuse` | 51 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 13 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2538 |
| `redis` | 694 |
| `mcp` | 405 |
| `llamacpp` | 268 |
| `litellm` | 184 |
| `vllm` | 172 |
| `jupyter` | 171 |
| `docker` | 132 |
| `ollama` | 130 |
| `hfhub` | 126 |
| `php` | 64 |
| `ray` | 31 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1581 |
| `345gs5662d34` | 1098 |
| `admin` | 737 |
| `ubuntu` | 368 |
| `user` | 185 |
| `ftpuser` | 182 |
| `test` | 140 |
| `guest` | 117 |
| `git` | 114 |
| `deploy` | 112 |
| `postgres` | 109 |
| `administrator` | 99 |
| `ftp` | 93 |
| `oracle` | 83 |
| `debian` | 77 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1087 |
| `123456` | 877 |
| `123` | 577 |
| `1234` | 408 |
| `12345678` | 323 |
| `admin` | 286 |
| `1` | 257 |
| `12345` | 256 |
| `P@ssw0rd` | 189 |
| `admin123` | 177 |
| `password` | 157 |
| `123456789` | 127 |
| `000000` | 125 |
| `!QAZ2wsx` | 109 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1465 |
| `cd` | 1274 |
| `cat` | 1272 |
| `echo` | 1260 |
| `crontab` | 1234 |
| `lscpu` | 1232 |
| `ls` | 1127 |
| `free` | 1125 |
| `df` | 1122 |
| `top` | 1122 |
| `w` | 1121 |
| `whoami` | 1121 |
| `INFO` | 459 |
| `canary_env` | 340 |
| `PING` | 326 |


_Generated from first-party honeypot capture. CC BY 4.0._
