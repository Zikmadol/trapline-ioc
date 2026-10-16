# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2498 attackers** · **484,549 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 166 |
| Used a planted canary credential | 20 |
| Seen on more than one sensor | 177 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1005 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 579 |
| `redis-exploit` | 475 |
| `mcp-abuse` | 193 |
| `llamacpp-abuse` | 58 |
| `litellm-key-replay` | 38 |
| `docker-abuse` | 26 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 11 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1637 |
| `redis` | 489 |
| `mcp` | 270 |
| `llamacpp` | 162 |
| `vllm` | 100 |
| `jupyter` | 96 |
| `litellm` | 91 |
| `hfhub` | 77 |
| `docker` | 68 |
| `ollama` | 48 |
| `ray` | 13 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 944 |
| `345gs5662d34` | 806 |
| `admin` | 546 |
| `ubuntu` | 258 |
| `user` | 137 |
| `ftpuser` | 124 |
| `test` | 122 |
| `git` | 85 |
| `postgres` | 81 |
| `administrator` | 80 |
| `deploy` | 80 |
| `guest` | 76 |
| `oracle` | 62 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 805 |
| `3245gs5662d34` | 801 |
| `123456` | 637 |
| `123` | 404 |
| `1234` | 307 |
| `12345678` | 213 |
| `admin` | 203 |
| `12345` | 190 |
| `1` | 183 |
| `password` | 139 |
| `P@ssw0rd` | 130 |
| `admin123` | 123 |
| `000000` | 102 |
| `123456789` | 101 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1109 |
| `echo` | 944 |
| `cd` | 943 |
| `cat` | 942 |
| `crontab` | 924 |
| `lscpu` | 923 |
| `ls` | 829 |
| `free` | 828 |
| `df` | 826 |
| `top` | 826 |
| `whoami` | 825 |
| `w` | 824 |
| `INFO` | 315 |
| `canary_env` | 232 |
| `PING` | 212 |


_Generated from first-party honeypot capture. CC BY 4.0._
