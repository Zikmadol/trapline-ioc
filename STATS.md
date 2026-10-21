# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2964 attackers** · **585,159 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 183 |
| Used a planted canary credential | 29 |
| Seen on more than one sensor | 208 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2576 |
| `ssh-exploit` | 1168 |
| `ssh-bruteforce` | 664 |
| `redis-exploit` | 546 |
| `mcp-abuse` | 231 |
| `llamacpp-abuse` | 76 |
| `ollama-abuse` | 55 |
| `litellm-key-replay` | 48 |
| `docker-abuse` | 35 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1906 |
| `redis` | 560 |
| `mcp` | 330 |
| `llamacpp` | 204 |
| `jupyter` | 130 |
| `vllm` | 125 |
| `litellm` | 117 |
| `hfhub` | 97 |
| `ollama` | 92 |
| `docker` | 85 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1086 |
| `345gs5662d34` | 933 |
| `admin` | 649 |
| `ubuntu` | 305 |
| `user` | 157 |
| `ftpuser` | 155 |
| `test` | 129 |
| `postgres` | 105 |
| `git` | 105 |
| `deploy` | 102 |
| `guest` | 95 |
| `administrator` | 91 |
| `oracle` | 72 |
| `ftp` | 69 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 931 |
| `3245gs5662d34` | 926 |
| `123456` | 762 |
| `123` | 499 |
| `1234` | 361 |
| `12345678` | 278 |
| `admin` | 234 |
| `12345` | 227 |
| `1` | 219 |
| `P@ssw0rd` | 162 |
| `password` | 158 |
| `admin123` | 146 |
| `000000` | 116 |
| `123456789` | 112 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1280 |
| `cat` | 1099 |
| `cd` | 1099 |
| `echo` | 1085 |
| `crontab` | 1063 |
| `lscpu` | 1061 |
| `ls` | 961 |
| `free` | 960 |
| `df` | 958 |
| `top` | 958 |
| `whoami` | 957 |
| `w` | 956 |
| `INFO` | 368 |
| `canary_env` | 284 |
| `PING` | 252 |


_Generated from first-party honeypot capture. CC BY 4.0._
