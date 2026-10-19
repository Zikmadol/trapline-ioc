# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2727 attackers** · **523,808 hostile actions** · covering 37 day(s) through 2026-10-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 193 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1848 |
| `ssh-exploit` | 1090 |
| `ssh-bruteforce` | 630 |
| `redis-exploit` | 509 |
| `mcp-abuse` | 217 |
| `llamacpp-abuse` | 66 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 36 |
| `docker-abuse` | 32 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1783 |
| `redis` | 523 |
| `mcp` | 304 |
| `llamacpp` | 180 |
| `vllm` | 108 |
| `jupyter` | 104 |
| `litellm` | 101 |
| `hfhub` | 86 |
| `docker` | 79 |
| `ollama` | 62 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1017 |
| `345gs5662d34` | 865 |
| `admin` | 615 |
| `ubuntu` | 297 |
| `user` | 153 |
| `ftpuser` | 141 |
| `test` | 123 |
| `git` | 98 |
| `deploy` | 94 |
| `postgres` | 93 |
| `guest` | 85 |
| `administrator` | 82 |
| `oracle` | 70 |
| `ftp` | 63 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 863 |
| `3245gs5662d34` | 861 |
| `123456` | 715 |
| `123` | 463 |
| `1234` | 339 |
| `12345678` | 257 |
| `admin` | 222 |
| `12345` | 214 |
| `1` | 203 |
| `password` | 152 |
| `P@ssw0rd` | 152 |
| `admin123` | 140 |
| `000000` | 110 |
| `123456789` | 106 |
| `!QAZ2wsx` | 97 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1199 |
| `cat` | 1024 |
| `cd` | 1024 |
| `echo` | 1012 |
| `crontab` | 989 |
| `lscpu` | 988 |
| `ls` | 890 |
| `free` | 889 |
| `df` | 887 |
| `top` | 887 |
| `whoami` | 886 |
| `w` | 885 |
| `INFO` | 340 |
| `canary_env` | 260 |
| `PING` | 232 |


_Generated from first-party honeypot capture. CC BY 4.0._
