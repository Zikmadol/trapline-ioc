# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3008 attackers** · **608,498 hostile actions** · covering 40 day(s) through 2026-10-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 185 |
| Used a planted canary credential | 33 |
| Seen on more than one sensor | 208 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2711 |
| `ssh-exploit` | 1188 |
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
| `ssh` | 1927 |
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
| `root` | 1102 |
| `345gs5662d34` | 950 |
| `admin` | 656 |
| `ubuntu` | 308 |
| `user` | 158 |
| `ftpuser` | 156 |
| `test` | 131 |
| `git` | 108 |
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
| `345gs5662d34` | 948 |
| `3245gs5662d34` | 942 |
| `123456` | 768 |
| `123` | 506 |
| `1234` | 365 |
| `12345678` | 281 |
| `admin` | 238 |
| `12345` | 228 |
| `1` | 224 |
| `P@ssw0rd` | 166 |
| `password` | 158 |
| `admin123` | 146 |
| `000000` | 118 |
| `123456789` | 115 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1298 |
| `cat` | 1116 |
| `cd` | 1116 |
| `echo` | 1102 |
| `crontab` | 1080 |
| `lscpu` | 1078 |
| `ls` | 977 |
| `free` | 976 |
| `df` | 974 |
| `top` | 974 |
| `whoami` | 973 |
| `w` | 972 |
| `INFO` | 375 |
| `canary_env` | 287 |
| `PING` | 257 |


_Generated from first-party honeypot capture. CC BY 4.0._
