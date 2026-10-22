# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2992 attackers** · **603,125 hostile actions** · covering 40 day(s) through 2026-10-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 185 |
| Used a planted canary credential | 31 |
| Seen on more than one sensor | 208 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2668 |
| `ssh-exploit` | 1181 |
| `ssh-bruteforce` | 666 |
| `redis-exploit` | 552 |
| `mcp-abuse` | 233 |
| `llamacpp-abuse` | 76 |
| `ollama-abuse` | 57 |
| `litellm-key-replay` | 49 |
| `docker-abuse` | 35 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1921 |
| `redis` | 566 |
| `mcp` | 334 |
| `llamacpp` | 207 |
| `jupyter` | 131 |
| `vllm` | 126 |
| `litellm` | 119 |
| `hfhub` | 97 |
| `ollama` | 97 |
| `docker` | 86 |
| `ray` | 20 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1096 |
| `345gs5662d34` | 945 |
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
| `345gs5662d34` | 943 |
| `3245gs5662d34` | 936 |
| `123456` | 767 |
| `123` | 507 |
| `1234` | 364 |
| `12345678` | 281 |
| `admin` | 238 |
| `12345` | 228 |
| `1` | 223 |
| `P@ssw0rd` | 163 |
| `password` | 157 |
| `admin123` | 146 |
| `000000` | 117 |
| `123456789` | 114 |
| `!QAZ2wsx` | 101 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1292 |
| `cat` | 1110 |
| `cd` | 1110 |
| `echo` | 1096 |
| `crontab` | 1074 |
| `lscpu` | 1072 |
| `ls` | 971 |
| `free` | 970 |
| `df` | 968 |
| `top` | 968 |
| `whoami` | 967 |
| `w` | 966 |
| `INFO` | 372 |
| `canary_env` | 285 |
| `PING` | 256 |


_Generated from first-party honeypot capture. CC BY 4.0._
