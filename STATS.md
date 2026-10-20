# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2881 attackers** · **571,469 hostile actions** · covering 38 day(s) through 2026-10-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 181 |
| Used a planted canary credential | 23 |
| Seen on more than one sensor | 204 |
| Stage-2 hosts named in payloads | 39 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2397 |
| `ssh-exploit` | 1128 |
| `ssh-bruteforce` | 654 |
| `redis-exploit` | 540 |
| `mcp-abuse` | 225 |
| `llamacpp-abuse` | 73 |
| `ollama-abuse` | 51 |
| `litellm-key-replay` | 47 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 31 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1852 |
| `redis` | 554 |
| `mcp` | 320 |
| `llamacpp` | 195 |
| `jupyter` | 126 |
| `vllm` | 122 |
| `litellm` | 112 |
| `hfhub` | 94 |
| `ollama` | 85 |
| `docker` | 82 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1053 |
| `345gs5662d34` | 898 |
| `admin` | 641 |
| `ubuntu` | 302 |
| `user` | 155 |
| `ftpuser` | 152 |
| `test` | 126 |
| `git` | 105 |
| `postgres` | 102 |
| `deploy` | 100 |
| `guest` | 92 |
| `administrator` | 89 |
| `oracle` | 72 |
| `ftp` | 67 |
| `dev` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 896 |
| `3245gs5662d34` | 892 |
| `123456` | 739 |
| `123` | 491 |
| `1234` | 349 |
| `12345678` | 273 |
| `admin` | 229 |
| `12345` | 224 |
| `1` | 215 |
| `P@ssw0rd` | 159 |
| `password` | 154 |
| `admin123` | 144 |
| `000000` | 114 |
| `123456789` | 111 |
| `!QAZ2wsx` | 99 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1240 |
| `cat` | 1062 |
| `cd` | 1062 |
| `echo` | 1047 |
| `crontab` | 1025 |
| `lscpu` | 1023 |
| `ls` | 924 |
| `free` | 923 |
| `df` | 921 |
| `top` | 921 |
| `whoami` | 920 |
| `w` | 919 |
| `INFO` | 364 |
| `canary_env` | 273 |
| `PING` | 248 |


_Generated from first-party honeypot capture. CC BY 4.0._
