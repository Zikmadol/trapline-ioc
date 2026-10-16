# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2526 attackers** · **488,834 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 167 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 178 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1016 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 585 |
| `redis-exploit` | 478 |
| `mcp-abuse` | 196 |
| `llamacpp-abuse` | 58 |
| `litellm-key-replay` | 40 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1654 |
| `redis` | 492 |
| `mcp` | 275 |
| `llamacpp` | 164 |
| `vllm` | 104 |
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
| `345gs5662d34` | 815 |
| `admin` | 555 |
| `ubuntu` | 266 |
| `user` | 143 |
| `ftpuser` | 128 |
| `test` | 123 |
| `git` | 85 |
| `deploy` | 85 |
| `postgres` | 82 |
| `administrator` | 80 |
| `guest` | 79 |
| `oracle` | 63 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 814 |
| `3245gs5662d34` | 809 |
| `123456` | 651 |
| `123` | 416 |
| `1234` | 315 |
| `12345678` | 224 |
| `admin` | 208 |
| `12345` | 195 |
| `1` | 184 |
| `password` | 140 |
| `P@ssw0rd` | 134 |
| `admin123` | 127 |
| `000000` | 103 |
| `123456789` | 100 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1120 |
| `echo` | 954 |
| `cd` | 953 |
| `cat` | 952 |
| `crontab` | 934 |
| `lscpu` | 933 |
| `ls` | 838 |
| `free` | 837 |
| `df` | 835 |
| `top` | 835 |
| `whoami` | 834 |
| `w` | 833 |
| `INFO` | 317 |
| `canary_env` | 236 |
| `PING` | 213 |


_Generated from first-party honeypot capture. CC BY 4.0._
