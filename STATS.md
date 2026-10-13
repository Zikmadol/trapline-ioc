# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2305 attackers** · **457,663 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 14 |
| Seen on more than one sensor | 165 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 937 |
| `ssh-bruteforce` | 535 |
| `redis-exploit` | 435 |
| `canary-aws-key` | 270 |
| `mcp-abuse` | 181 |
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
| `ssh` | 1521 |
| `redis` | 448 |
| `mcp` | 251 |
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
| `root` | 871 |
| `345gs5662d34` | 748 |
| `admin` | 501 |
| `ubuntu` | 246 |
| `user` | 123 |
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
| `345gs5662d34` | 747 |
| `3245gs5662d34` | 744 |
| `123456` | 573 |
| `123` | 365 |
| `1234` | 286 |
| `12345678` | 190 |
| `admin` | 184 |
| `12345` | 178 |
| `1` | 161 |
| `password` | 125 |
| `P@ssw0rd` | 116 |
| `admin123` | 109 |
| `000000` | 98 |
| `123456789` | 95 |
| `!QAZ2wsx` | 87 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1025 |
| `echo` | 875 |
| `cd` | 873 |
| `cat` | 872 |
| `crontab` | 856 |
| `lscpu` | 856 |
| `ls` | 769 |
| `free` | 768 |
| `top` | 768 |
| `df` | 767 |
| `whoami` | 766 |
| `w` | 765 |
| `INFO` | 293 |
| `canary_env` | 217 |
| `PING` | 194 |


_Generated from first-party honeypot capture. CC BY 4.0._
