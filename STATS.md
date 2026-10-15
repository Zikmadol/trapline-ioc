# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2473 attackers** · **479,563 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 166 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 176 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 997 |
| `canary-aws-key` | 795 |
| `ssh-bruteforce` | 573 |
| `redis-exploit` | 470 |
| `mcp-abuse` | 192 |
| `llamacpp-abuse` | 56 |
| `litellm-key-replay` | 38 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 11 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1623 |
| `redis` | 483 |
| `mcp` | 268 |
| `llamacpp` | 158 |
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
| `root` | 933 |
| `345gs5662d34` | 796 |
| `admin` | 540 |
| `ubuntu` | 254 |
| `user` | 134 |
| `ftpuser` | 121 |
| `test` | 120 |
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
| `345gs5662d34` | 795 |
| `3245gs5662d34` | 792 |
| `123456` | 627 |
| `123` | 397 |
| `1234` | 305 |
| `12345678` | 213 |
| `admin` | 200 |
| `12345` | 189 |
| `1` | 177 |
| `password` | 137 |
| `P@ssw0rd` | 130 |
| `admin123` | 123 |
| `123456789` | 102 |
| `000000` | 101 |
| `!QAZ2wsx` | 92 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1099 |
| `echo` | 934 |
| `cd` | 933 |
| `cat` | 932 |
| `crontab` | 914 |
| `lscpu` | 913 |
| `ls` | 819 |
| `free` | 818 |
| `df` | 816 |
| `top` | 816 |
| `whoami` | 815 |
| `w` | 814 |
| `INFO` | 312 |
| `canary_env` | 230 |
| `PING` | 209 |


_Generated from first-party honeypot capture. CC BY 4.0._
