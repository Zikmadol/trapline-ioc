# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2310 attackers** · **457,997 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 15 |
| Seen on more than one sensor | 165 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 938 |
| `ssh-bruteforce` | 537 |
| `redis-exploit` | 435 |
| `canary-aws-key` | 299 |
| `mcp-abuse` | 182 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 34 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1524 |
| `redis` | 448 |
| `mcp` | 252 |
| `llamacpp` | 140 |
| `jupyter` | 88 |
| `vllm` | 88 |
| `litellm` | 78 |
| `hfhub` | 70 |
| `docker` | 60 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 873 |
| `345gs5662d34` | 749 |
| `admin` | 503 |
| `ubuntu` | 247 |
| `user` | 122 |
| `ftpuser` | 114 |
| `test` | 110 |
| `administrator` | 79 |
| `postgres` | 77 |
| `git` | 77 |
| `guest` | 70 |
| `deploy` | 67 |
| `admin1` | 59 |
| `AdminGPON` | 57 |
| `oracle` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 748 |
| `3245gs5662d34` | 745 |
| `123456` | 573 |
| `123` | 365 |
| `1234` | 286 |
| `12345678` | 190 |
| `admin` | 184 |
| `12345` | 178 |
| `1` | 161 |
| `password` | 126 |
| `P@ssw0rd` | 116 |
| `admin123` | 109 |
| `000000` | 98 |
| `123456789` | 95 |
| `!QAZ2wsx` | 87 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1026 |
| `echo` | 876 |
| `cd` | 874 |
| `cat` | 873 |
| `crontab` | 857 |
| `lscpu` | 857 |
| `ls` | 770 |
| `free` | 769 |
| `top` | 769 |
| `df` | 768 |
| `whoami` | 767 |
| `w` | 766 |
| `INFO` | 293 |
| `canary_env` | 218 |
| `PING` | 194 |


_Generated from first-party honeypot capture. CC BY 4.0._
