# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2774 attackers** · **540,226 hostile actions** · covering 37 day(s) through 2026-10-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 176 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 196 |
| Stage-2 hosts named in payloads | 38 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2096 |
| `ssh-exploit` | 1107 |
| `ssh-bruteforce` | 637 |
| `redis-exploit` | 520 |
| `mcp-abuse` | 218 |
| `llamacpp-abuse` | 71 |
| `litellm-key-replay` | 45 |
| `ollama-abuse` | 37 |
| `docker-abuse` | 33 |
| `vllm-abuse` | 13 |
| `jupyter-abuse` | 13 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1810 |
| `redis` | 534 |
| `mcp` | 309 |
| `llamacpp` | 189 |
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
| `root` | 1028 |
| `345gs5662d34` | 877 |
| `admin` | 623 |
| `ubuntu` | 305 |
| `user` | 153 |
| `ftpuser` | 144 |
| `test` | 123 |
| `git` | 99 |
| `postgres` | 96 |
| `deploy` | 95 |
| `guest` | 87 |
| `administrator` | 82 |
| `oracle` | 72 |
| `ftp` | 64 |
| `debian` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 875 |
| `3245gs5662d34` | 873 |
| `123456` | 727 |
| `123` | 474 |
| `1234` | 345 |
| `12345678` | 261 |
| `admin` | 226 |
| `12345` | 221 |
| `1` | 205 |
| `P@ssw0rd` | 156 |
| `password` | 152 |
| `admin123` | 142 |
| `000000` | 111 |
| `123456789` | 109 |
| `!QAZ2wsx` | 98 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1217 |
| `cat` | 1040 |
| `cd` | 1040 |
| `echo` | 1024 |
| `crontab` | 1002 |
| `lscpu` | 1000 |
| `ls` | 902 |
| `free` | 901 |
| `df` | 899 |
| `top` | 899 |
| `whoami` | 898 |
| `w` | 897 |
| `INFO` | 349 |
| `canary_env` | 263 |
| `PING` | 238 |


_Generated from first-party honeypot capture. CC BY 4.0._
