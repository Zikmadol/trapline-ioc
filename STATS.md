# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2862 attackers** · **570,328 hostile actions** · covering 38 day(s) through 2026-10-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 180 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 200 |
| Stage-2 hosts named in payloads | 39 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2341 |
| `ssh-exploit` | 1125 |
| `ssh-bruteforce` | 651 |
| `redis-exploit` | 536 |
| `mcp-abuse` | 224 |
| `llamacpp-abuse` | 73 |
| `litellm-key-replay` | 46 |
| `ollama-abuse` | 45 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 31 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1845 |
| `redis` | 550 |
| `mcp` | 318 |
| `llamacpp` | 194 |
| `jupyter` | 126 |
| `vllm` | 121 |
| `litellm` | 111 |
| `hfhub` | 94 |
| `docker` | 82 |
| `ollama` | 77 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1048 |
| `345gs5662d34` | 894 |
| `admin` | 639 |
| `ubuntu` | 302 |
| `user` | 154 |
| `ftpuser` | 152 |
| `test` | 126 |
| `git` | 104 |
| `postgres` | 102 |
| `deploy` | 99 |
| `guest` | 92 |
| `administrator` | 89 |
| `oracle` | 72 |
| `ftp` | 66 |
| `dev` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 892 |
| `3245gs5662d34` | 889 |
| `123456` | 739 |
| `123` | 491 |
| `1234` | 348 |
| `12345678` | 272 |
| `admin` | 229 |
| `12345` | 223 |
| `1` | 214 |
| `P@ssw0rd` | 159 |
| `password` | 153 |
| `admin123` | 144 |
| `000000` | 114 |
| `123456789` | 111 |
| `!QAZ2wsx` | 99 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1236 |
| `cat` | 1058 |
| `cd` | 1058 |
| `echo` | 1043 |
| `crontab` | 1021 |
| `lscpu` | 1019 |
| `ls` | 920 |
| `free` | 919 |
| `df` | 917 |
| `top` | 917 |
| `whoami` | 916 |
| `w` | 915 |
| `INFO` | 361 |
| `canary_env` | 272 |
| `PING` | 246 |


_Generated from first-party honeypot capture. CC BY 4.0._
