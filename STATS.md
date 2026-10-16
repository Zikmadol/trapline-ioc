# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2521 attackers** · **488,556 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 167 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 178 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1014 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 585 |
| `redis-exploit` | 478 |
| `mcp-abuse` | 194 |
| `llamacpp-abuse` | 57 |
| `litellm-key-replay` | 40 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1652 |
| `redis` | 492 |
| `mcp` | 273 |
| `llamacpp` | 163 |
| `vllm` | 103 |
| `jupyter` | 96 |
| `litellm` | 94 |
| `hfhub` | 79 |
| `docker` | 69 |
| `ollama` | 48 |
| `ray` | 13 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 957 |
| `345gs5662d34` | 814 |
| `admin` | 553 |
| `ubuntu` | 266 |
| `user` | 143 |
| `ftpuser` | 127 |
| `test` | 123 |
| `git` | 85 |
| `deploy` | 85 |
| `postgres` | 81 |
| `administrator` | 80 |
| `guest` | 78 |
| `oracle` | 63 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 813 |
| `3245gs5662d34` | 808 |
| `123456` | 649 |
| `123` | 416 |
| `1234` | 313 |
| `12345678` | 222 |
| `admin` | 207 |
| `12345` | 194 |
| `1` | 184 |
| `password` | 139 |
| `P@ssw0rd` | 132 |
| `admin123` | 126 |
| `000000` | 103 |
| `123456789` | 100 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1119 |
| `echo` | 953 |
| `cd` | 952 |
| `cat` | 951 |
| `crontab` | 933 |
| `lscpu` | 932 |
| `ls` | 837 |
| `free` | 836 |
| `df` | 834 |
| `top` | 834 |
| `whoami` | 833 |
| `w` | 832 |
| `INFO` | 317 |
| `canary_env` | 233 |
| `PING` | 213 |


_Generated from first-party honeypot capture. CC BY 4.0._
