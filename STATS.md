# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2978 attackers** · **586,629 hostile actions** · covering 40 day(s) through 2026-10-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 184 |
| Used a planted canary credential | 30 |
| Seen on more than one sensor | 208 |
| Stage-2 hosts named in payloads | 40 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2614 |
| `ssh-exploit` | 1177 |
| `ssh-bruteforce` | 665 |
| `redis-exploit` | 549 |
| `mcp-abuse` | 231 |
| `llamacpp-abuse` | 76 |
| `ollama-abuse` | 55 |
| `litellm-key-replay` | 48 |
| `docker-abuse` | 35 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1916 |
| `redis` | 563 |
| `mcp` | 332 |
| `llamacpp` | 206 |
| `jupyter` | 130 |
| `vllm` | 125 |
| `litellm` | 117 |
| `hfhub` | 97 |
| `ollama` | 92 |
| `docker` | 86 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1094 |
| `345gs5662d34` | 943 |
| `admin` | 653 |
| `ubuntu` | 306 |
| `user` | 159 |
| `ftpuser` | 155 |
| `test` | 130 |
| `git` | 108 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 95 |
| `administrator` | 91 |
| `oracle` | 72 |
| `ftp` | 69 |
| `dev` | 66 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 941 |
| `3245gs5662d34` | 934 |
| `123456` | 767 |
| `123` | 506 |
| `1234` | 364 |
| `12345678` | 278 |
| `admin` | 235 |
| `12345` | 228 |
| `1` | 222 |
| `P@ssw0rd` | 162 |
| `password` | 157 |
| `admin123` | 145 |
| `000000` | 116 |
| `123456789` | 114 |
| `!QAZ2wsx` | 100 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1289 |
| `cat` | 1108 |
| `cd` | 1108 |
| `echo` | 1094 |
| `crontab` | 1072 |
| `lscpu` | 1070 |
| `ls` | 969 |
| `free` | 968 |
| `df` | 966 |
| `top` | 966 |
| `whoami` | 965 |
| `w` | 964 |
| `INFO` | 370 |
| `canary_env` | 284 |
| `PING` | 254 |


_Generated from first-party honeypot capture. CC BY 4.0._
