# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2514 attackers** · **487,125 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 167 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 178 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1010 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 585 |
| `redis-exploit` | 477 |
| `mcp-abuse` | 194 |
| `llamacpp-abuse` | 57 |
| `litellm-key-replay` | 38 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1648 |
| `redis` | 491 |
| `mcp` | 272 |
| `llamacpp` | 163 |
| `vllm` | 102 |
| `jupyter` | 96 |
| `litellm` | 91 |
| `hfhub` | 79 |
| `docker` | 69 |
| `ollama` | 48 |
| `ray` | 13 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 953 |
| `345gs5662d34` | 810 |
| `admin` | 549 |
| `ubuntu` | 262 |
| `user` | 139 |
| `ftpuser` | 127 |
| `test` | 122 |
| `git` | 85 |
| `deploy` | 82 |
| `postgres` | 81 |
| `administrator` | 80 |
| `guest` | 77 |
| `oracle` | 63 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 809 |
| `3245gs5662d34` | 804 |
| `123456` | 646 |
| `123` | 411 |
| `1234` | 311 |
| `12345678` | 219 |
| `admin` | 207 |
| `12345` | 192 |
| `1` | 184 |
| `password` | 139 |
| `P@ssw0rd` | 132 |
| `admin123` | 125 |
| `000000` | 103 |
| `123456789` | 100 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1115 |
| `echo` | 949 |
| `cd` | 948 |
| `cat` | 947 |
| `crontab` | 929 |
| `lscpu` | 928 |
| `ls` | 833 |
| `free` | 832 |
| `df` | 830 |
| `top` | 830 |
| `whoami` | 829 |
| `w` | 828 |
| `INFO` | 317 |
| `canary_env` | 233 |
| `PING` | 213 |


_Generated from first-party honeypot capture. CC BY 4.0._
