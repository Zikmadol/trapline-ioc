# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2970 attackers** · **585,931 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 183 |
| Used a planted canary credential | 30 |
| Seen on more than one sensor | 208 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2599 |
| `ssh-exploit` | 1172 |
| `ssh-bruteforce` | 664 |
| `redis-exploit` | 547 |
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
| `ssh` | 1910 |
| `redis` | 561 |
| `mcp` | 330 |
| `llamacpp` | 205 |
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
| `root` | 1090 |
| `345gs5662d34` | 938 |
| `admin` | 652 |
| `ubuntu` | 306 |
| `user` | 158 |
| `ftpuser` | 155 |
| `test` | 129 |
| `git` | 107 |
| `postgres` | 104 |
| `deploy` | 104 |
| `guest` | 95 |
| `administrator` | 91 |
| `oracle` | 72 |
| `ftp` | 69 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 936 |
| `3245gs5662d34` | 931 |
| `123456` | 763 |
| `123` | 503 |
| `1234` | 362 |
| `12345678` | 278 |
| `admin` | 234 |
| `12345` | 228 |
| `1` | 222 |
| `P@ssw0rd` | 162 |
| `password` | 158 |
| `admin123` | 146 |
| `000000` | 116 |
| `123456789` | 113 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1284 |
| `cat` | 1104 |
| `cd` | 1104 |
| `echo` | 1089 |
| `crontab` | 1067 |
| `lscpu` | 1065 |
| `ls` | 965 |
| `free` | 964 |
| `df` | 962 |
| `top` | 962 |
| `whoami` | 961 |
| `w` | 960 |
| `INFO` | 369 |
| `canary_env` | 284 |
| `PING` | 252 |


_Generated from first-party honeypot capture. CC BY 4.0._
