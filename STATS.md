# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2768 attackers** · **539,141 hostile actions** · covering 37 day(s) through 2026-10-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 176 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 195 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2074 |
| `ssh-exploit` | 1106 |
| `ssh-bruteforce` | 636 |
| `redis-exploit` | 519 |
| `mcp-abuse` | 218 |
| `llamacpp-abuse` | 71 |
| `litellm-key-replay` | 45 |
| `ollama-abuse` | 36 |
| `docker-abuse` | 32 |
| `vllm-abuse` | 13 |
| `jupyter-abuse` | 13 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1808 |
| `redis` | 533 |
| `mcp` | 309 |
| `llamacpp` | 188 |
| `vllm` | 110 |
| `jupyter` | 107 |
| `litellm` | 107 |
| `hfhub` | 90 |
| `docker` | 80 |
| `ollama` | 64 |
| `ray` | 15 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1026 |
| `345gs5662d34` | 876 |
| `admin` | 624 |
| `ubuntu` | 305 |
| `user` | 153 |
| `ftpuser` | 144 |
| `test` | 123 |
| `git` | 99 |
| `postgres` | 95 |
| `deploy` | 95 |
| `guest` | 87 |
| `administrator` | 83 |
| `oracle` | 72 |
| `ftp` | 64 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 874 |
| `3245gs5662d34` | 872 |
| `123456` | 725 |
| `123` | 473 |
| `1234` | 345 |
| `12345678` | 261 |
| `admin` | 226 |
| `12345` | 221 |
| `1` | 205 |
| `P@ssw0rd` | 156 |
| `password` | 152 |
| `admin123` | 142 |
| `000000` | 111 |
| `123456789` | 109 |
| `!QAZ2wsx` | 98 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1215 |
| `cat` | 1039 |
| `cd` | 1039 |
| `echo` | 1023 |
| `crontab` | 1001 |
| `lscpu` | 999 |
| `ls` | 901 |
| `free` | 900 |
| `df` | 898 |
| `top` | 898 |
| `whoami` | 897 |
| `w` | 896 |
| `INFO` | 348 |
| `canary_env` | 263 |
| `PING` | 238 |


_Generated from first-party honeypot capture. CC BY 4.0._
