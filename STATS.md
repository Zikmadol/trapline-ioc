# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2547 attackers** · **497,029 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 172 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 181 |
| Stage-2 hosts named in payloads | 36 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1020 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 592 |
| `redis-exploit` | 484 |
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
| `ssh` | 1666 |
| `redis` | 498 |
| `mcp` | 277 |
| `llamacpp` | 166 |
| `vllm` | 104 |
| `jupyter` | 98 |
| `litellm` | 95 |
| `hfhub` | 81 |
| `docker` | 70 |
| `ollama` | 48 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 962 |
| `345gs5662d34` | 816 |
| `admin` | 558 |
| `ubuntu` | 269 |
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
| `123456` | 655 |
| `123` | 417 |
| `1234` | 316 |
| `12345678` | 229 |
| `admin` | 209 |
| `12345` | 196 |
| `1` | 186 |
| `password` | 140 |
| `P@ssw0rd` | 139 |
| `admin123` | 127 |
| `000000` | 105 |
| `123456789` | 101 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1125 |
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
| `INFO` | 322 |
| `canary_env` | 239 |
| `PING` | 215 |


_Generated from first-party honeypot capture. CC BY 4.0._
