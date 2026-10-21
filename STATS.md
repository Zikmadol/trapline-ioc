# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2934 attackers** · **578,635 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 183 |
| Used a planted canary credential | 28 |
| Seen on more than one sensor | 206 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2531 |
| `ssh-exploit` | 1151 |
| `ssh-bruteforce` | 663 |
| `redis-exploit` | 544 |
| `mcp-abuse` | 228 |
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
| `ssh` | 1887 |
| `redis` | 558 |
| `mcp` | 327 |
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
| `root` | 1073 |
| `345gs5662d34` | 917 |
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
| `345gs5662d34` | 915 |
| `3245gs5662d34` | 910 |
| `123456` | 750 |
| `123` | 498 |
| `1234` | 356 |
| `12345678` | 275 |
| `admin` | 233 |
| `12345` | 226 |
| `1` | 218 |
| `P@ssw0rd` | 160 |
| `password` | 155 |
| `admin123` | 145 |
| `000000` | 115 |
| `123456789` | 111 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1263 |
| `cat` | 1083 |
| `cd` | 1083 |
| `echo` | 1069 |
| `crontab` | 1047 |
| `lscpu` | 1045 |
| `ls` | 945 |
| `free` | 944 |
| `df` | 942 |
| `top` | 942 |
| `whoami` | 941 |
| `w` | 940 |
| `INFO` | 367 |
| `canary_env` | 277 |
| `PING` | 251 |


_Generated from first-party honeypot capture. CC BY 4.0._
