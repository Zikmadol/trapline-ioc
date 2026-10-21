# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2888 attackers** · **576,814 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 182 |
| Used a planted canary credential | 23 |
| Seen on more than one sensor | 205 |
| Stage-2 hosts named in payloads | 39 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2437 |
| `ssh-exploit` | 1131 |
| `ssh-bruteforce` | 656 |
| `redis-exploit` | 540 |
| `mcp-abuse` | 226 |
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
| `ssh` | 1859 |
| `redis` | 554 |
| `mcp` | 324 |
| `llamacpp` | 197 |
| `jupyter` | 127 |
| `vllm` | 122 |
| `litellm` | 112 |
| `hfhub` | 94 |
| `ollama` | 85 |
| `docker` | 82 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1057 |
| `345gs5662d34` | 900 |
| `admin` | 643 |
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
| `345gs5662d34` | 898 |
| `3245gs5662d34` | 894 |
| `123456` | 742 |
| `123` | 491 |
| `1234` | 349 |
| `12345678` | 273 |
| `admin` | 229 |
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
| `uname` | 1244 |
| `cat` | 1064 |
| `cd` | 1064 |
| `echo` | 1050 |
| `crontab` | 1028 |
| `lscpu` | 1026 |
| `ls` | 926 |
| `free` | 925 |
| `df` | 923 |
| `top` | 923 |
| `whoami` | 922 |
| `w` | 921 |
| `INFO` | 364 |
| `canary_env` | 274 |
| `PING` | 248 |


_Generated from first-party honeypot capture. CC BY 4.0._
