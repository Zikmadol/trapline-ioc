# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2925 attackers** · **578,508 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 183 |
| Used a planted canary credential | 28 |
| Seen on more than one sensor | 206 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2526 |
| `ssh-exploit` | 1147 |
| `ssh-bruteforce` | 659 |
| `redis-exploit` | 544 |
| `mcp-abuse` | 227 |
| `llamacpp-abuse` | 74 |
| `ollama-abuse` | 55 |
| `litellm-key-replay` | 47 |
| `docker-abuse` | 34 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1879 |
| `redis` | 558 |
| `mcp` | 326 |
| `llamacpp` | 200 |
| `jupyter` | 128 |
| `vllm` | 124 |
| `litellm` | 114 |
| `hfhub` | 95 |
| `ollama` | 91 |
| `docker` | 83 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1068 |
| `345gs5662d34` | 913 |
| `admin` | 646 |
| `ubuntu` | 304 |
| `user` | 156 |
| `ftpuser` | 153 |
| `test` | 126 |
| `git` | 105 |
| `postgres` | 103 |
| `deploy` | 102 |
| `guest` | 93 |
| `administrator` | 90 |
| `oracle` | 72 |
| `ftp` | 68 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 911 |
| `3245gs5662d34` | 907 |
| `123456` | 748 |
| `123` | 498 |
| `1234` | 356 |
| `12345678` | 275 |
| `admin` | 233 |
| `12345` | 226 |
| `1` | 216 |
| `P@ssw0rd` | 160 |
| `password` | 155 |
| `admin123` | 145 |
| `000000` | 115 |
| `123456789` | 111 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1259 |
| `cat` | 1079 |
| `cd` | 1079 |
| `echo` | 1065 |
| `crontab` | 1043 |
| `lscpu` | 1041 |
| `ls` | 941 |
| `free` | 940 |
| `df` | 938 |
| `top` | 938 |
| `whoami` | 937 |
| `w` | 936 |
| `INFO` | 367 |
| `canary_env` | 276 |
| `PING` | 251 |


_Generated from first-party honeypot capture. CC BY 4.0._
