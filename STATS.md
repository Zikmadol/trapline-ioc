# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2509 attackers** · **486,814 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 167 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 178 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1007 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 583 |
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
| `ssh` | 1643 |
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
| `root` | 951 |
| `345gs5662d34` | 810 |
| `admin` | 548 |
| `ubuntu` | 261 |
| `user` | 139 |
| `ftpuser` | 126 |
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
| `123456` | 643 |
| `123` | 410 |
| `1234` | 310 |
| `12345678` | 219 |
| `admin` | 206 |
| `12345` | 192 |
| `1` | 184 |
| `password` | 139 |
| `P@ssw0rd` | 132 |
| `admin123` | 124 |
| `000000` | 103 |
| `123456789` | 100 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1113 |
| `echo` | 948 |
| `cd` | 946 |
| `cat` | 945 |
| `crontab` | 928 |
| `lscpu` | 927 |
| `ls` | 832 |
| `free` | 831 |
| `df` | 829 |
| `top` | 829 |
| `whoami` | 828 |
| `w` | 827 |
| `INFO` | 317 |
| `canary_env` | 233 |
| `PING` | 213 |


_Generated from first-party honeypot capture. CC BY 4.0._
