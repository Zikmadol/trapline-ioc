# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2759 attackers** · **532,958 hostile actions** · covering 37 day(s) through 2026-10-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 176 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 195 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2006 |
| `ssh-exploit` | 1102 |
| `ssh-bruteforce` | 633 |
| `redis-exploit` | 517 |
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
| `ssh` | 1801 |
| `redis` | 531 |
| `mcp` | 307 |
| `llamacpp` | 187 |
| `vllm` | 110 |
| `jupyter` | 106 |
| `litellm` | 105 |
| `hfhub` | 89 |
| `docker` | 79 |
| `ollama` | 63 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1024 |
| `345gs5662d34` | 873 |
| `admin` | 621 |
| `ubuntu` | 303 |
| `user` | 153 |
| `ftpuser` | 144 |
| `test` | 123 |
| `git` | 99 |
| `postgres` | 95 |
| `deploy` | 95 |
| `guest` | 87 |
| `administrator` | 83 |
| `oracle` | 71 |
| `ftp` | 64 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 871 |
| `3245gs5662d34` | 869 |
| `123456` | 724 |
| `123` | 473 |
| `1234` | 343 |
| `12345678` | 260 |
| `admin` | 225 |
| `12345` | 221 |
| `1` | 204 |
| `P@ssw0rd` | 155 |
| `password` | 152 |
| `admin123` | 141 |
| `000000` | 111 |
| `123456789` | 109 |
| `!QAZ2wsx` | 98 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1210 |
| `cat` | 1034 |
| `cd` | 1034 |
| `echo` | 1020 |
| `crontab` | 998 |
| `lscpu` | 996 |
| `ls` | 898 |
| `free` | 897 |
| `df` | 895 |
| `top` | 895 |
| `whoami` | 894 |
| `w` | 893 |
| `INFO` | 346 |
| `canary_env` | 263 |
| `PING` | 237 |


_Generated from first-party honeypot capture. CC BY 4.0._
