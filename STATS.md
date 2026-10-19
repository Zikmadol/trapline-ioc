# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2780 attackers** · **541,124 hostile actions** · covering 37 day(s) through 2026-10-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 176 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 196 |
| Stage-2 hosts named in payloads | 38 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2109 |
| `ssh-exploit` | 1112 |
| `ssh-bruteforce` | 637 |
| `redis-exploit` | 520 |
| `mcp-abuse` | 218 |
| `llamacpp-abuse` | 72 |
| `litellm-key-replay` | 45 |
| `ollama-abuse` | 37 |
| `docker-abuse` | 33 |
| `vllm-abuse` | 13 |
| `jupyter-abuse` | 13 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1815 |
| `redis` | 534 |
| `mcp` | 309 |
| `llamacpp` | 190 |
| `vllm` | 110 |
| `jupyter` | 107 |
| `litellm` | 107 |
| `hfhub` | 91 |
| `docker` | 81 |
| `ollama` | 65 |
| `ray` | 15 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1030 |
| `345gs5662d34` | 881 |
| `admin` | 630 |
| `ubuntu` | 304 |
| `user` | 156 |
| `ftpuser` | 145 |
| `test` | 124 |
| `git` | 99 |
| `postgres` | 96 |
| `deploy` | 95 |
| `guest` | 87 |
| `administrator` | 82 |
| `oracle` | 72 |
| `dev` | 65 |
| `ftp` | 64 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 879 |
| `3245gs5662d34` | 877 |
| `123456` | 728 |
| `123` | 479 |
| `1234` | 345 |
| `12345678` | 268 |
| `admin` | 226 |
| `12345` | 221 |
| `1` | 211 |
| `P@ssw0rd` | 156 |
| `password` | 152 |
| `admin123` | 142 |
| `000000` | 111 |
| `123456789` | 109 |
| `!QAZ2wsx` | 98 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1222 |
| `cat` | 1045 |
| `cd` | 1045 |
| `echo` | 1029 |
| `crontab` | 1007 |
| `lscpu` | 1005 |
| `ls` | 907 |
| `free` | 906 |
| `df` | 904 |
| `top` | 904 |
| `whoami` | 903 |
| `w` | 902 |
| `INFO` | 349 |
| `canary_env` | 264 |
| `PING` | 238 |


_Generated from first-party honeypot capture. CC BY 4.0._
