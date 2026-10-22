# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3006 attackers** · **608,341 hostile actions** · covering 40 day(s) through 2026-10-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 185 |
| Used a planted canary credential | 33 |
| Seen on more than one sensor | 208 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2703 |
| `ssh-exploit` | 1186 |
| `ssh-bruteforce` | 665 |
| `redis-exploit` | 555 |
| `mcp-abuse` | 234 |
| `llamacpp-abuse` | 77 |
| `ollama-abuse` | 57 |
| `litellm-key-replay` | 52 |
| `docker-abuse` | 36 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1925 |
| `redis` | 569 |
| `mcp` | 335 |
| `llamacpp` | 209 |
| `jupyter` | 131 |
| `vllm` | 126 |
| `litellm` | 121 |
| `ollama` | 98 |
| `hfhub` | 97 |
| `docker` | 87 |
| `ray` | 20 |
| `php` | 5 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1100 |
| `345gs5662d34` | 949 |
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
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 947 |
| `3245gs5662d34` | 940 |
| `123456` | 768 |
| `123` | 506 |
| `1234` | 364 |
| `12345678` | 281 |
| `admin` | 238 |
| `12345` | 228 |
| `1` | 222 |
| `P@ssw0rd` | 165 |
| `password` | 158 |
| `admin123` | 146 |
| `000000` | 118 |
| `123456789` | 114 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1296 |
| `cat` | 1114 |
| `cd` | 1114 |
| `echo` | 1100 |
| `crontab` | 1078 |
| `lscpu` | 1076 |
| `ls` | 975 |
| `free` | 974 |
| `df` | 972 |
| `top` | 972 |
| `whoami` | 971 |
| `w` | 970 |
| `INFO` | 375 |
| `canary_env` | 287 |
| `PING` | 257 |


_Generated from first-party honeypot capture. CC BY 4.0._
