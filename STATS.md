# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2458 attackers** · **478,474 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 165 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 176 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 993 |
| `canary-aws-key` | 794 |
| `ssh-bruteforce` | 570 |
| `redis-exploit` | 470 |
| `mcp-abuse` | 190 |
| `llamacpp-abuse` | 54 |
| `litellm-key-replay` | 37 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1616 |
| `redis` | 483 |
| `mcp` | 266 |
| `llamacpp` | 156 |
| `vllm` | 98 |
| `jupyter` | 95 |
| `litellm` | 89 |
| `hfhub` | 75 |
| `docker` | 66 |
| `ollama` | 48 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 927 |
| `345gs5662d34` | 793 |
| `admin` | 537 |
| `ubuntu` | 254 |
| `user` | 132 |
| `ftpuser` | 121 |
| `test` | 118 |
| `git` | 82 |
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
| `345gs5662d34` | 792 |
| `3245gs5662d34` | 789 |
| `123456` | 625 |
| `123` | 394 |
| `1234` | 303 |
| `12345678` | 211 |
| `admin` | 198 |
| `12345` | 189 |
| `1` | 175 |
| `password` | 137 |
| `P@ssw0rd` | 128 |
| `admin123` | 123 |
| `123456789` | 102 |
| `000000` | 101 |
| `!QAZ2wsx` | 92 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1094 |
| `cd` | 930 |
| `echo` | 930 |
| `cat` | 928 |
| `crontab` | 911 |
| `lscpu` | 910 |
| `ls` | 815 |
| `free` | 814 |
| `top` | 813 |
| `df` | 812 |
| `w` | 811 |
| `whoami` | 811 |
| `INFO` | 312 |
| `canary_env` | 227 |
| `PING` | 209 |


_Generated from first-party honeypot capture. CC BY 4.0._
