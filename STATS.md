# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2455 attackers** · **478,185 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 165 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 175 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 990 |
| `canary-aws-key` | 793 |
| `ssh-bruteforce` | 571 |
| `redis-exploit` | 469 |
| `mcp-abuse` | 190 |
| `llamacpp-abuse` | 54 |
| `litellm-key-replay` | 37 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1613 |
| `redis` | 482 |
| `mcp` | 266 |
| `llamacpp` | 156 |
| `vllm` | 98 |
| `jupyter` | 94 |
| `litellm` | 88 |
| `hfhub` | 75 |
| `docker` | 66 |
| `ollama` | 47 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 925 |
| `345gs5662d34` | 791 |
| `admin` | 535 |
| `ubuntu` | 254 |
| `user` | 132 |
| `ftpuser` | 121 |
| `test` | 118 |
| `git` | 82 |
| `administrator` | 80 |
| `postgres` | 78 |
| `deploy` | 78 |
| `guest` | 75 |
| `oracle` | 62 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 790 |
| `3245gs5662d34` | 787 |
| `123456` | 624 |
| `123` | 393 |
| `1234` | 302 |
| `12345678` | 211 |
| `admin` | 198 |
| `12345` | 189 |
| `1` | 174 |
| `password` | 134 |
| `P@ssw0rd` | 128 |
| `admin123` | 123 |
| `123456789` | 102 |
| `000000` | 101 |
| `!QAZ2wsx` | 92 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1092 |
| `cd` | 928 |
| `echo` | 928 |
| `cat` | 926 |
| `crontab` | 909 |
| `lscpu` | 908 |
| `ls` | 813 |
| `free` | 812 |
| `top` | 811 |
| `df` | 810 |
| `w` | 809 |
| `whoami` | 809 |
| `INFO` | 311 |
| `canary_env` | 227 |
| `PING` | 208 |


_Generated from first-party honeypot capture. CC BY 4.0._
