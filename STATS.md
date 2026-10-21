# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2954 attackers** · **579,830 hostile actions** · covering 39 day(s) through 2026-10-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 183 |
| Used a planted canary credential | 28 |
| Seen on more than one sensor | 206 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2554 |
| `ssh-exploit` | 1167 |
| `ssh-bruteforce` | 661 |
| `redis-exploit` | 545 |
| `mcp-abuse` | 231 |
| `llamacpp-abuse` | 75 |
| `ollama-abuse` | 55 |
| `litellm-key-replay` | 47 |
| `docker-abuse` | 35 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1901 |
| `redis` | 559 |
| `mcp` | 330 |
| `llamacpp` | 201 |
| `jupyter` | 129 |
| `vllm` | 124 |
| `litellm` | 114 |
| `hfhub` | 95 |
| `ollama` | 91 |
| `docker` | 84 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1085 |
| `345gs5662d34` | 933 |
| `admin` | 647 |
| `ubuntu` | 305 |
| `user` | 157 |
| `ftpuser` | 154 |
| `test` | 129 |
| `postgres` | 105 |
| `git` | 105 |
| `deploy` | 102 |
| `guest` | 94 |
| `administrator` | 91 |
| `oracle` | 72 |
| `ftp` | 68 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 931 |
| `3245gs5662d34` | 926 |
| `123456` | 761 |
| `123` | 499 |
| `1234` | 360 |
| `12345678` | 277 |
| `admin` | 232 |
| `12345` | 226 |
| `1` | 218 |
| `P@ssw0rd` | 161 |
| `password` | 158 |
| `admin123` | 145 |
| `000000` | 115 |
| `123456789` | 111 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1279 |
| `cat` | 1099 |
| `cd` | 1099 |
| `echo` | 1085 |
| `crontab` | 1063 |
| `lscpu` | 1061 |
| `ls` | 961 |
| `free` | 960 |
| `df` | 958 |
| `top` | 958 |
| `whoami` | 957 |
| `w` | 956 |
| `INFO` | 367 |
| `canary_env` | 281 |
| `PING` | 252 |


_Generated from first-party honeypot capture. CC BY 4.0._
