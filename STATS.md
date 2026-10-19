# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2750 attackers** · **527,344 hostile actions** · covering 37 day(s) through 2026-10-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 176 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 193 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1940 |
| `ssh-exploit` | 1100 |
| `ssh-bruteforce` | 633 |
| `redis-exploit` | 513 |
| `mcp-abuse` | 218 |
| `llamacpp-abuse` | 69 |
| `litellm-key-replay` | 45 |
| `ollama-abuse` | 36 |
| `docker-abuse` | 32 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1797 |
| `redis` | 527 |
| `mcp` | 305 |
| `llamacpp` | 184 |
| `vllm` | 108 |
| `jupyter` | 105 |
| `litellm` | 104 |
| `hfhub` | 87 |
| `docker` | 79 |
| `ollama` | 62 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1023 |
| `345gs5662d34` | 872 |
| `admin` | 620 |
| `ubuntu` | 303 |
| `user` | 153 |
| `ftpuser` | 144 |
| `test` | 123 |
| `git` | 99 |
| `deploy` | 95 |
| `postgres` | 94 |
| `guest` | 87 |
| `administrator` | 83 |
| `oracle` | 71 |
| `ftp` | 64 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 870 |
| `3245gs5662d34` | 868 |
| `123456` | 723 |
| `123` | 473 |
| `1234` | 342 |
| `12345678` | 260 |
| `admin` | 225 |
| `12345` | 221 |
| `1` | 204 |
| `P@ssw0rd` | 155 |
| `password` | 152 |
| `admin123` | 141 |
| `000000` | 110 |
| `123456789` | 109 |
| `!QAZ2wsx` | 98 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1209 |
| `cat` | 1033 |
| `cd` | 1033 |
| `echo` | 1019 |
| `crontab` | 997 |
| `lscpu` | 995 |
| `ls` | 897 |
| `free` | 896 |
| `df` | 894 |
| `top` | 894 |
| `whoami` | 893 |
| `w` | 892 |
| `INFO` | 343 |
| `canary_env` | 261 |
| `PING` | 234 |


_Generated from first-party honeypot capture. CC BY 4.0._
