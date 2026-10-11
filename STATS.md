# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2161 attackers** · **434,529 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 147 |
| Used a planted canary credential | 9 |
| Seen on more than one sensor | 152 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 892 |
| `ssh-bruteforce` | 500 |
| `redis-exploit` | 405 |
| `mcp-abuse` | 162 |
| `llamacpp-abuse` | 45 |
| `litellm-key-replay` | 32 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 22 |
| `canary-aws-key` | 19 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1435 |
| `redis` | 417 |
| `mcp` | 223 |
| `llamacpp` | 127 |
| `jupyter` | 80 |
| `vllm` | 78 |
| `litellm` | 70 |
| `hfhub` | 66 |
| `docker` | 52 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 827 |
| `345gs5662d34` | 713 |
| `admin` | 471 |
| `ubuntu` | 225 |
| `user` | 110 |
| `test` | 105 |
| `ftpuser` | 104 |
| `administrator` | 76 |
| `git` | 69 |
| `postgres` | 66 |
| `guest` | 64 |
| `deploy` | 63 |
| `admin1` | 58 |
| `AdminGPON` | 56 |
| `oracle` | 56 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 712 |
| `345gs5662d34` | 712 |
| `123456` | 532 |
| `123` | 339 |
| `1234` | 268 |
| `12345678` | 177 |
| `admin` | 172 |
| `12345` | 167 |
| `1` | 151 |
| `password` | 114 |
| `P@ssw0rd` | 105 |
| `admin123` | 100 |
| `000000` | 96 |
| `123456789` | 89 |
| `!QAZ2wsx` | 82 |

### Top commands run

| command | times |
|---|---|
| `uname` | 972 |
| `echo` | 832 |
| `cd` | 826 |
| `cat` | 824 |
| `crontab` | 815 |
| `lscpu` | 815 |
| `ls` | 732 |
| `top` | 731 |
| `df` | 730 |
| `free` | 730 |
| `whoami` | 729 |
| `w` | 728 |
| `INFO` | 269 |
| `canary_env` | 195 |
| `PING` | 186 |


_Generated from first-party honeypot capture. CC BY 4.0._
