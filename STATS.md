# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2996 attackers** · **607,952 hostile actions** · covering 40 day(s) through 2026-10-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 185 |
| Used a planted canary credential | 32 |
| Seen on more than one sensor | 208 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2686 |
| `ssh-exploit` | 1183 |
| `ssh-bruteforce` | 665 |
| `redis-exploit` | 552 |
| `mcp-abuse` | 234 |
| `llamacpp-abuse` | 76 |
| `ollama-abuse` | 57 |
| `litellm-key-replay` | 50 |
| `docker-abuse` | 35 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1922 |
| `redis` | 566 |
| `mcp` | 335 |
| `llamacpp` | 207 |
| `jupyter` | 131 |
| `vllm` | 126 |
| `litellm` | 119 |
| `ollama` | 98 |
| `hfhub` | 97 |
| `docker` | 86 |
| `ray` | 20 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1096 |
| `345gs5662d34` | 946 |
| `admin` | 656 |
| `ubuntu` | 307 |
| `user` | 158 |
| `ftpuser` | 156 |
| `test` | 131 |
| `git` | 107 |
| `deploy` | 105 |
| `postgres` | 104 |
| `guest` | 96 |
| `administrator` | 92 |
| `oracle` | 72 |
| `ftp` | 70 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 944 |
| `3245gs5662d34` | 937 |
| `123456` | 768 |
| `123` | 506 |
| `1234` | 364 |
| `12345678` | 281 |
| `admin` | 238 |
| `12345` | 228 |
| `1` | 222 |
| `P@ssw0rd` | 163 |
| `password` | 157 |
| `admin123` | 146 |
| `000000` | 118 |
| `123456789` | 114 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1293 |
| `cat` | 1111 |
| `cd` | 1111 |
| `echo` | 1097 |
| `crontab` | 1075 |
| `lscpu` | 1073 |
| `ls` | 972 |
| `free` | 971 |
| `df` | 969 |
| `top` | 969 |
| `whoami` | 968 |
| `w` | 967 |
| `INFO` | 372 |
| `canary_env` | 286 |
| `PING` | 256 |


_Generated from first-party honeypot capture. CC BY 4.0._
