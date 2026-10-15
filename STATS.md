# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2431 attackers** · **475,068 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 163 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 982 |
| `canary-aws-key` | 792 |
| `ssh-bruteforce` | 564 |
| `redis-exploit` | 464 |
| `mcp-abuse` | 189 |
| `llamacpp-abuse` | 52 |
| `litellm-key-replay` | 36 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1598 |
| `redis` | 477 |
| `mcp` | 265 |
| `llamacpp` | 153 |
| `vllm` | 97 |
| `jupyter` | 93 |
| `litellm` | 87 |
| `hfhub` | 74 |
| `docker` | 65 |
| `ollama` | 47 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 914 |
| `345gs5662d34` | 782 |
| `admin` | 534 |
| `ubuntu` | 253 |
| `user` | 129 |
| `ftpuser` | 120 |
| `test` | 118 |
| `administrator` | 81 |
| `git` | 81 |
| `postgres` | 79 |
| `guest` | 75 |
| `deploy` | 75 |
| `oracle` | 62 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 781 |
| `3245gs5662d34` | 778 |
| `123456` | 617 |
| `123` | 387 |
| `1234` | 299 |
| `12345678` | 205 |
| `admin` | 195 |
| `12345` | 188 |
| `1` | 172 |
| `password` | 129 |
| `P@ssw0rd` | 127 |
| `admin123` | 121 |
| `123456789` | 101 |
| `000000` | 100 |
| `!QAZ2wsx` | 91 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1081 |
| `cd` | 919 |
| `cat` | 917 |
| `echo` | 917 |
| `crontab` | 898 |
| `lscpu` | 897 |
| `ls` | 804 |
| `free` | 803 |
| `top` | 802 |
| `df` | 801 |
| `w` | 800 |
| `whoami` | 800 |
| `INFO` | 309 |
| `canary_env` | 225 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
