# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2947 attackers** · **579,332 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 183 |
| Used a planted canary credential | 28 |
| Seen on more than one sensor | 206 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2544 |
| `ssh-exploit` | 1162 |
| `ssh-bruteforce` | 660 |
| `redis-exploit` | 545 |
| `mcp-abuse` | 230 |
| `llamacpp-abuse` | 75 |
| `ollama-abuse` | 55 |
| `litellm-key-replay` | 47 |
| `docker-abuse` | 35 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1895 |
| `redis` | 559 |
| `mcp` | 329 |
| `llamacpp` | 201 |
| `jupyter` | 129 |
| `vllm` | 124 |
| `litellm` | 114 |
| `hfhub` | 95 |
| `ollama` | 91 |
| `docker` | 84 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1082 |
| `345gs5662d34` | 928 |
| `admin` | 647 |
| `ubuntu` | 304 |
| `user` | 157 |
| `ftpuser` | 153 |
| `test` | 127 |
| `postgres` | 105 |
| `git` | 105 |
| `deploy` | 102 |
| `guest` | 94 |
| `administrator` | 90 |
| `oracle` | 72 |
| `ftp` | 68 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 926 |
| `3245gs5662d34` | 921 |
| `123456` | 758 |
| `123` | 499 |
| `1234` | 360 |
| `12345678` | 277 |
| `admin` | 232 |
| `12345` | 226 |
| `1` | 218 |
| `P@ssw0rd` | 160 |
| `password` | 155 |
| `admin123` | 145 |
| `000000` | 115 |
| `123456789` | 111 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1274 |
| `cat` | 1094 |
| `cd` | 1094 |
| `echo` | 1080 |
| `crontab` | 1058 |
| `lscpu` | 1056 |
| `ls` | 956 |
| `free` | 955 |
| `df` | 953 |
| `top` | 953 |
| `whoami` | 952 |
| `w` | 951 |
| `INFO` | 367 |
| `canary_env` | 280 |
| `PING` | 252 |


_Generated from first-party honeypot capture. CC BY 4.0._
