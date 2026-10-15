# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2468 attackers** · **479,278 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 166 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 176 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 995 |
| `canary-aws-key` | 795 |
| `ssh-bruteforce` | 572 |
| `redis-exploit` | 470 |
| `mcp-abuse` | 192 |
| `llamacpp-abuse` | 54 |
| `litellm-key-replay` | 38 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 11 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1620 |
| `redis` | 483 |
| `mcp` | 268 |
| `llamacpp` | 156 |
| `vllm` | 99 |
| `jupyter` | 96 |
| `litellm` | 90 |
| `hfhub` | 75 |
| `docker` | 67 |
| `ollama` | 48 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 930 |
| `345gs5662d34` | 794 |
| `admin` | 540 |
| `ubuntu` | 254 |
| `user` | 134 |
| `ftpuser` | 121 |
| `test` | 119 |
| `git` | 83 |
| `administrator` | 80 |
| `postgres` | 78 |
| `deploy` | 78 |
| `guest` | 75 |
| `oracle` | 62 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 793 |
| `3245gs5662d34` | 790 |
| `123456` | 627 |
| `123` | 397 |
| `1234` | 304 |
| `12345678` | 213 |
| `admin` | 200 |
| `12345` | 189 |
| `1` | 177 |
| `password` | 137 |
| `P@ssw0rd` | 128 |
| `admin123` | 123 |
| `123456789` | 102 |
| `000000` | 101 |
| `!QAZ2wsx` | 92 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1097 |
| `echo` | 932 |
| `cd` | 931 |
| `cat` | 930 |
| `crontab` | 912 |
| `lscpu` | 911 |
| `ls` | 817 |
| `free` | 816 |
| `df` | 814 |
| `top` | 814 |
| `whoami` | 813 |
| `w` | 812 |
| `INFO` | 312 |
| `canary_env` | 230 |
| `PING` | 209 |


_Generated from first-party honeypot capture. CC BY 4.0._
