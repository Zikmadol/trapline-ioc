# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2443 attackers** · **475,969 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 163 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 989 |
| `canary-aws-key` | 793 |
| `ssh-bruteforce` | 566 |
| `redis-exploit` | 465 |
| `mcp-abuse` | 190 |
| `llamacpp-abuse` | 53 |
| `litellm-key-replay` | 36 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1607 |
| `redis` | 478 |
| `mcp` | 266 |
| `llamacpp` | 154 |
| `vllm` | 97 |
| `jupyter` | 93 |
| `litellm` | 87 |
| `hfhub` | 74 |
| `docker` | 65 |
| `ollama` | 47 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 922 |
| `345gs5662d34` | 789 |
| `admin` | 534 |
| `ubuntu` | 254 |
| `user` | 129 |
| `ftpuser` | 120 |
| `test` | 118 |
| `administrator` | 81 |
| `git` | 81 |
| `postgres` | 78 |
| `deploy` | 78 |
| `guest` | 74 |
| `oracle` | 62 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 788 |
| `3245gs5662d34` | 785 |
| `123456` | 622 |
| `123` | 390 |
| `1234` | 301 |
| `12345678` | 210 |
| `admin` | 196 |
| `12345` | 188 |
| `1` | 172 |
| `password` | 132 |
| `P@ssw0rd` | 127 |
| `admin123` | 122 |
| `123456789` | 102 |
| `000000` | 100 |
| `!QAZ2wsx` | 91 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1089 |
| `cd` | 926 |
| `cat` | 924 |
| `echo` | 924 |
| `crontab` | 905 |
| `lscpu` | 904 |
| `ls` | 811 |
| `free` | 810 |
| `top` | 809 |
| `df` | 808 |
| `w` | 807 |
| `whoami` | 807 |
| `INFO` | 309 |
| `canary_env` | 226 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
