# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2841 attackers** · **553,788 hostile actions** · covering 38 day(s) through 2026-10-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 180 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 198 |
| Stage-2 hosts named in payloads | 38 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2260 |
| `ssh-exploit` | 1117 |
| `ssh-bruteforce` | 650 |
| `redis-exploit` | 529 |
| `mcp-abuse` | 223 |
| `llamacpp-abuse` | 73 |
| `litellm-key-replay` | 46 |
| `ollama-abuse` | 43 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 31 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1834 |
| `redis` | 543 |
| `mcp` | 316 |
| `llamacpp` | 193 |
| `jupyter` | 126 |
| `vllm` | 116 |
| `litellm` | 111 |
| `hfhub` | 93 |
| `docker` | 82 |
| `ollama` | 74 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1044 |
| `345gs5662d34` | 888 |
| `admin` | 635 |
| `ubuntu` | 303 |
| `user` | 154 |
| `ftpuser` | 150 |
| `test` | 126 |
| `postgres` | 102 |
| `git` | 99 |
| `deploy` | 96 |
| `guest` | 89 |
| `administrator` | 89 |
| `oracle` | 72 |
| `dev` | 65 |
| `ftp` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 886 |
| `3245gs5662d34` | 884 |
| `123456` | 736 |
| `123` | 486 |
| `1234` | 346 |
| `12345678` | 270 |
| `admin` | 228 |
| `12345` | 222 |
| `1` | 213 |
| `P@ssw0rd` | 157 |
| `password` | 153 |
| `admin123` | 143 |
| `000000` | 113 |
| `123456789` | 109 |
| `!QAZ2wsx` | 99 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1230 |
| `cd` | 1053 |
| `cat` | 1052 |
| `echo` | 1037 |
| `crontab` | 1015 |
| `lscpu` | 1013 |
| `ls` | 914 |
| `free` | 913 |
| `df` | 911 |
| `top` | 911 |
| `whoami` | 910 |
| `w` | 909 |
| `INFO` | 356 |
| `canary_env` | 271 |
| `PING` | 243 |


_Generated from first-party honeypot capture. CC BY 4.0._
