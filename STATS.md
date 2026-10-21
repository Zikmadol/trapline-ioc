# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2917 attackers** · **578,189 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 182 |
| Used a planted canary credential | 28 |
| Seen on more than one sensor | 205 |
| Stage-2 hosts named in payloads | 39 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2494 |
| `ssh-exploit` | 1146 |
| `ssh-bruteforce` | 657 |
| `redis-exploit` | 542 |
| `mcp-abuse` | 227 |
| `llamacpp-abuse` | 74 |
| `ollama-abuse` | 54 |
| `litellm-key-replay` | 47 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1875 |
| `redis` | 556 |
| `mcp` | 326 |
| `llamacpp` | 199 |
| `jupyter` | 128 |
| `vllm` | 124 |
| `litellm` | 113 |
| `hfhub` | 95 |
| `ollama` | 89 |
| `docker` | 82 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1068 |
| `345gs5662d34` | 912 |
| `admin` | 645 |
| `ubuntu` | 304 |
| `user` | 156 |
| `ftpuser` | 152 |
| `test` | 126 |
| `git` | 105 |
| `postgres` | 103 |
| `deploy` | 102 |
| `guest` | 92 |
| `administrator` | 90 |
| `oracle` | 72 |
| `ftp` | 67 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 910 |
| `3245gs5662d34` | 906 |
| `123456` | 746 |
| `123` | 498 |
| `1234` | 355 |
| `12345678` | 274 |
| `admin` | 232 |
| `12345` | 225 |
| `1` | 215 |
| `P@ssw0rd` | 159 |
| `password` | 155 |
| `admin123` | 144 |
| `000000` | 115 |
| `123456789` | 111 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1258 |
| `cat` | 1078 |
| `cd` | 1078 |
| `echo` | 1064 |
| `crontab` | 1042 |
| `lscpu` | 1040 |
| `ls` | 940 |
| `free` | 939 |
| `df` | 937 |
| `top` | 937 |
| `whoami` | 936 |
| `w` | 935 |
| `INFO` | 365 |
| `canary_env` | 276 |
| `PING` | 250 |


_Generated from first-party honeypot capture. CC BY 4.0._
