# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2834 attackers** · **553,462 hostile actions** · covering 38 day(s) through 2026-10-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 180 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 198 |
| Stage-2 hosts named in payloads | 38 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2249 |
| `ssh-exploit` | 1114 |
| `ssh-bruteforce` | 647 |
| `redis-exploit` | 529 |
| `mcp-abuse` | 223 |
| `llamacpp-abuse` | 73 |
| `litellm-key-replay` | 46 |
| `ollama-abuse` | 43 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 30 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1828 |
| `redis` | 543 |
| `mcp` | 315 |
| `llamacpp` | 193 |
| `jupyter` | 125 |
| `vllm` | 116 |
| `litellm` | 111 |
| `hfhub` | 93 |
| `docker` | 82 |
| `ollama` | 74 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1039 |
| `345gs5662d34` | 885 |
| `admin` | 633 |
| `ubuntu` | 303 |
| `user` | 155 |
| `ftpuser` | 148 |
| `test` | 127 |
| `postgres` | 102 |
| `git` | 99 |
| `deploy` | 95 |
| `administrator` | 89 |
| `guest` | 88 |
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
| `admin` | 228 |
| `12345` | 222 |
| `1` | 213 |
| `P@ssw0rd` | 157 |
| `password` | 153 |
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
| `INFO` | 356 |
| `canary_env` | 271 |
| `PING` | 243 |


_Generated from first-party honeypot capture. CC BY 4.0._
