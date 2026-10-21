# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2897 attackers** · **577,161 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 182 |
| Used a planted canary credential | 28 |
| Seen on more than one sensor | 205 |
| Stage-2 hosts named in payloads | 39 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2455 |
| `ssh-exploit` | 1134 |
| `ssh-bruteforce` | 656 |
| `redis-exploit` | 540 |
| `mcp-abuse` | 227 |
| `llamacpp-abuse` | 73 |
| `ollama-abuse` | 51 |
| `litellm-key-replay` | 47 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1862 |
| `redis` | 554 |
| `mcp` | 325 |
| `llamacpp` | 197 |
| `jupyter` | 128 |
| `vllm` | 123 |
| `litellm` | 112 |
| `hfhub` | 94 |
| `ollama` | 85 |
| `docker` | 82 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1060 |
| `345gs5662d34` | 902 |
| `admin` | 644 |
| `ubuntu` | 303 |
| `user` | 155 |
| `ftpuser` | 152 |
| `test` | 126 |
| `git` | 105 |
| `postgres` | 103 |
| `deploy` | 100 |
| `guest` | 92 |
| `administrator` | 90 |
| `oracle` | 72 |
| `ftp` | 67 |
| `dev` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 900 |
| `3245gs5662d34` | 896 |
| `123456` | 743 |
| `123` | 491 |
| `1234` | 352 |
| `12345678` | 273 |
| `admin` | 230 |
| `12345` | 224 |
| `1` | 215 |
| `P@ssw0rd` | 159 |
| `password` | 155 |
| `admin123` | 144 |
| `000000` | 115 |
| `123456789` | 111 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1247 |
| `cat` | 1067 |
| `cd` | 1067 |
| `echo` | 1053 |
| `crontab` | 1031 |
| `lscpu` | 1029 |
| `ls` | 929 |
| `free` | 928 |
| `df` | 926 |
| `top` | 926 |
| `whoami` | 925 |
| `w` | 924 |
| `INFO` | 364 |
| `canary_env` | 275 |
| `PING` | 248 |


_Generated from first-party honeypot capture. CC BY 4.0._
