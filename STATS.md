# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2543 attackers** · **496,898 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 170 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 180 |
| Stage-2 hosts named in payloads | 36 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1019 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 590 |
| `redis-exploit` | 483 |
| `mcp-abuse` | 198 |
| `llamacpp-abuse` | 59 |
| `litellm-key-replay` | 40 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1663 |
| `redis` | 497 |
| `mcp` | 277 |
| `llamacpp` | 166 |
| `vllm` | 104 |
| `jupyter` | 98 |
| `litellm` | 95 |
| `hfhub` | 81 |
| `docker` | 69 |
| `ollama` | 48 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 960 |
| `345gs5662d34` | 816 |
| `admin` | 556 |
| `ubuntu` | 268 |
| `user` | 144 |
| `ftpuser` | 130 |
| `test` | 123 |
| `git` | 86 |
| `deploy` | 85 |
| `postgres` | 82 |
| `administrator` | 80 |
| `guest` | 79 |
| `oracle` | 63 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 814 |
| `3245gs5662d34` | 810 |
| `123456` | 653 |
| `123` | 417 |
| `1234` | 316 |
| `12345678` | 228 |
| `admin` | 209 |
| `12345` | 196 |
| `1` | 186 |
| `password` | 140 |
| `P@ssw0rd` | 138 |
| `admin123` | 127 |
| `000000` | 105 |
| `123456789` | 101 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1124 |
| `echo` | 958 |
| `cd` | 955 |
| `cat` | 954 |
| `crontab` | 938 |
| `lscpu` | 937 |
| `ls` | 840 |
| `free` | 839 |
| `df` | 837 |
| `top` | 837 |
| `whoami` | 836 |
| `w` | 835 |
| `INFO` | 321 |
| `canary_env` | 239 |
| `PING` | 215 |


_Generated from first-party honeypot capture. CC BY 4.0._
