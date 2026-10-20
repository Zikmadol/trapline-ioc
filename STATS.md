# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2816 attackers** · **547,027 hostile actions** · covering 38 day(s) through 2026-10-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 177 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 198 |
| Stage-2 hosts named in payloads | 38 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2199 |
| `ssh-exploit` | 1113 |
| `ssh-bruteforce` | 646 |
| `redis-exploit` | 526 |
| `mcp-abuse` | 221 |
| `llamacpp-abuse` | 73 |
| `litellm-key-replay` | 45 |
| `ollama-abuse` | 42 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 24 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1826 |
| `redis` | 540 |
| `mcp` | 313 |
| `llamacpp` | 192 |
| `jupyter` | 119 |
| `vllm` | 111 |
| `litellm` | 109 |
| `hfhub` | 91 |
| `docker` | 82 |
| `ollama` | 70 |
| `ray` | 15 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1039 |
| `345gs5662d34` | 885 |
| `admin` | 632 |
| `ubuntu` | 302 |
| `user` | 155 |
| `ftpuser` | 148 |
| `test` | 127 |
| `postgres` | 102 |
| `git` | 99 |
| `deploy` | 95 |
| `guest` | 88 |
| `administrator` | 88 |
| `oracle` | 72 |
| `dev` | 65 |
| `ftp` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 883 |
| `3245gs5662d34` | 881 |
| `123456` | 731 |
| `123` | 482 |
| `1234` | 346 |
| `12345678` | 270 |
| `admin` | 227 |
| `12345` | 222 |
| `1` | 213 |
| `P@ssw0rd` | 157 |
| `password` | 152 |
| `admin123` | 143 |
| `000000` | 113 |
| `123456789` | 109 |
| `!QAZ2wsx` | 99 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1227 |
| `cat` | 1049 |
| `cd` | 1049 |
| `echo` | 1034 |
| `crontab` | 1012 |
| `lscpu` | 1010 |
| `ls` | 911 |
| `free` | 910 |
| `df` | 908 |
| `top` | 908 |
| `whoami` | 907 |
| `w` | 906 |
| `INFO` | 354 |
| `canary_env` | 269 |
| `PING` | 241 |


_Generated from first-party honeypot capture. CC BY 4.0._
