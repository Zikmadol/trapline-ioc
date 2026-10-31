# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3950 attackers** · **767,962 hostile actions** · covering 49 day(s) through 2026-10-31

| signal | count |
|---|---|
| GPU / AI-hardware probing | 208 |
| Used a planted canary credential | 55 |
| Seen on more than one sensor | 281 |
| Stage-2 hosts named in payloads | 52 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5181 |
| `ssh-exploit` | 1353 |
| `ssh-bruteforce` | 1115 |
| `redis-exploit` | 682 |
| `mcp-abuse` | 267 |
| `litellm-key-replay` | 103 |
| `llamacpp-abuse` | 89 |
| `ollama-abuse` | 77 |
| `docker-abuse` | 52 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 15 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2559 |
| `redis` | 701 |
| `mcp` | 409 |
| `llamacpp` | 279 |
| `litellm` | 197 |
| `vllm` | 175 |
| `jupyter` | 174 |
| `docker` | 133 |
| `ollama` | 132 |
| `hfhub` | 128 |
| `php` | 65 |
| `ray` | 32 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1585 |
| `345gs5662d34` | 1098 |
| `admin` | 749 |
| `ubuntu` | 376 |
| `user` | 187 |
| `ftpuser` | 184 |
| `test` | 141 |
| `guest` | 122 |
| `git` | 114 |
| `deploy` | 113 |
| `postgres` | 109 |
| `administrator` | 99 |
| `ftp` | 97 |
| `oracle` | 84 |
| `debian` | 77 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 887 |
| `123` | 582 |
| `1234` | 412 |
| `12345678` | 331 |
| `admin` | 292 |
| `1` | 261 |
| `12345` | 260 |
| `P@ssw0rd` | 193 |
| `admin123` | 183 |
| `password` | 158 |
| `123456789` | 128 |
| `000000` | 125 |
| `!QAZ2wsx` | 110 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1472 |
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
| `INFO` | 462 |
| `canary_env` | 343 |
| `PING` | 330 |


_Generated from first-party honeypot capture. CC BY 4.0._
