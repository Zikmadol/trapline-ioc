# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3971 attackers** · **774,831 hostile actions** · covering 50 day(s) through 2026-11-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 208 |
| Used a planted canary credential | 56 |
| Seen on more than one sensor | 284 |
| Stage-2 hosts named in payloads | 54 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5305 |
| `ssh-exploit` | 1353 |
| `ssh-bruteforce` | 1122 |
| `redis-exploit` | 685 |
| `mcp-abuse` | 268 |
| `litellm-key-replay` | 106 |
| `llamacpp-abuse` | 89 |
| `ollama-abuse` | 79 |
| `docker-abuse` | 52 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 15 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2566 |
| `redis` | 704 |
| `mcp` | 413 |
| `llamacpp` | 283 |
| `litellm` | 200 |
| `vllm` | 177 |
| `jupyter` | 174 |
| `docker` | 135 |
| `ollama` | 133 |
| `hfhub` | 129 |
| `php` | 68 |
| `ray` | 32 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1594 |
| `345gs5662d34` | 1098 |
| `admin` | 755 |
| `ubuntu` | 380 |
| `user` | 187 |
| `ftpuser` | 184 |
| `test` | 145 |
| `guest` | 122 |
| `git` | 114 |
| `deploy` | 113 |
| `postgres` | 109 |
| `administrator` | 100 |
| `ftp` | 97 |
| `oracle` | 84 |
| `debian` | 77 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 891 |
| `123` | 583 |
| `1234` | 414 |
| `12345678` | 333 |
| `admin` | 293 |
| `1` | 263 |
| `12345` | 261 |
| `P@ssw0rd` | 193 |
| `admin123` | 183 |
| `password` | 158 |
| `123456789` | 130 |
| `000000` | 125 |
| `!QAZ2wsx` | 110 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1473 |
| `cd` | 1280 |
| `cat` | 1278 |
| `echo` | 1261 |
| `crontab` | 1236 |
| `lscpu` | 1233 |
| `ls` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `whoami` | 1123 |
| `w` | 1122 |
| `INFO` | 464 |
| `canary_env` | 347 |
| `PING` | 332 |


_Generated from first-party honeypot capture. CC BY 4.0._
