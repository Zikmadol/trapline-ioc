# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2652 attackers** · **513,196 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 174 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 189 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1055 |
| `canary-aws-key` | 1013 |
| `ssh-bruteforce` | 617 |
| `redis-exploit` | 500 |
| `mcp-abuse` | 208 |
| `llamacpp-abuse` | 64 |
| `litellm-key-replay` | 42 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 30 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1731 |
| `redis` | 514 |
| `mcp` | 292 |
| `llamacpp` | 174 |
| `vllm` | 107 |
| `jupyter` | 102 |
| `litellm` | 99 |
| `hfhub` | 83 |
| `docker` | 75 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 980 |
| `345gs5662d34` | 833 |
| `admin` | 582 |
| `ubuntu` | 281 |
| `user` | 148 |
| `ftpuser` | 138 |
| `test` | 122 |
| `git` | 89 |
| `deploy` | 87 |
| `postgres` | 86 |
| `guest` | 82 |
| `administrator` | 82 |
| `oracle` | 66 |
| `admin1` | 59 |
| `ftp` | 58 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 831 |
| `3245gs5662d34` | 830 |
| `123456` | 683 |
| `123` | 440 |
| `1234` | 322 |
| `12345678` | 239 |
| `admin` | 216 |
| `12345` | 203 |
| `1` | 196 |
| `password` | 145 |
| `P@ssw0rd` | 141 |
| `admin123` | 137 |
| `000000` | 109 |
| `123456789` | 105 |
| `!QAZ2wsx` | 95 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1161 |
| `cd` | 988 |
| `cat` | 987 |
| `echo` | 978 |
| `crontab` | 957 |
| `lscpu` | 956 |
| `ls` | 858 |
| `free` | 857 |
| `df` | 855 |
| `top` | 855 |
| `whoami` | 854 |
| `w` | 853 |
| `INFO` | 332 |
| `canary_env` | 251 |
| `PING` | 225 |


_Generated from first-party honeypot capture. CC BY 4.0._
