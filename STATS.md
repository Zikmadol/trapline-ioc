# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2165 attackers** · **435,212 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 147 |
| Used a planted canary credential | 9 |
| Seen on more than one sensor | 152 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 893 |
| `ssh-bruteforce` | 503 |
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
| `ssh` | 1439 |
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
| `root` | 828 |
| `345gs5662d34` | 714 |
| `admin` | 474 |
| `ubuntu` | 225 |
| `user` | 110 |
| `test` | 105 |
| `ftpuser` | 105 |
| `administrator` | 76 |
| `git` | 69 |
| `postgres` | 66 |
| `guest` | 65 |
| `deploy` | 63 |
| `admin1` | 58 |
| `AdminGPON` | 56 |
| `oracle` | 56 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 713 |
| `345gs5662d34` | 713 |
| `123456` | 533 |
| `123` | 339 |
| `1234` | 269 |
| `12345678` | 178 |
| `admin` | 176 |
| `12345` | 168 |
| `1` | 151 |
| `password` | 113 |
| `P@ssw0rd` | 106 |
| `admin123` | 101 |
| `000000` | 96 |
| `123456789` | 89 |
| `!QAZ2wsx` | 83 |

### Top commands run

| command | times |
|---|---|
| `uname` | 973 |
| `echo` | 833 |
| `cd` | 827 |
| `cat` | 825 |
| `crontab` | 816 |
| `lscpu` | 816 |
| `ls` | 733 |
| `top` | 732 |
| `df` | 731 |
| `free` | 731 |
| `whoami` | 730 |
| `w` | 729 |
| `INFO` | 269 |
| `canary_env` | 195 |
| `PING` | 186 |


_Generated from first-party honeypot capture. CC BY 4.0._
