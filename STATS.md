# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2657 attackers** · **513,943 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 174 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 189 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1057 |
| `canary-aws-key` | 1054 |
| `ssh-bruteforce` | 617 |
| `redis-exploit` | 500 |
| `mcp-abuse` | 209 |
| `llamacpp-abuse` | 64 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 31 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1733 |
| `redis` | 514 |
| `mcp` | 293 |
| `llamacpp` | 174 |
| `vllm` | 107 |
| `jupyter` | 102 |
| `litellm` | 100 |
| `hfhub` | 83 |
| `docker` | 76 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 983 |
| `345gs5662d34` | 837 |
| `admin` | 586 |
| `ubuntu` | 283 |
| `user` | 148 |
| `ftpuser` | 138 |
| `test` | 122 |
| `git` | 89 |
| `deploy` | 89 |
| `postgres` | 86 |
| `guest` | 82 |
| `administrator` | 82 |
| `oracle` | 66 |
| `admin1` | 59 |
| `ftp` | 58 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 835 |
| `3245gs5662d34` | 834 |
| `123456` | 685 |
| `123` | 440 |
| `1234` | 323 |
| `12345678` | 239 |
| `admin` | 216 |
| `12345` | 203 |
| `1` | 198 |
| `password` | 145 |
| `P@ssw0rd` | 141 |
| `admin123` | 137 |
| `000000` | 109 |
| `123456789` | 105 |
| `!QAZ2wsx` | 95 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1165 |
| `cd` | 992 |
| `cat` | 991 |
| `echo` | 982 |
| `crontab` | 961 |
| `lscpu` | 960 |
| `ls` | 862 |
| `free` | 861 |
| `df` | 859 |
| `top` | 859 |
| `whoami` | 858 |
| `w` | 857 |
| `INFO` | 332 |
| `canary_env` | 252 |
| `PING` | 225 |


_Generated from first-party honeypot capture. CC BY 4.0._
