# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2537 attackers** · **495,697 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 169 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 179 |
| Stage-2 hosts named in payloads | 36 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1016 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 588 |
| `redis-exploit` | 482 |
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
| `ssh` | 1657 |
| `redis` | 496 |
| `mcp` | 277 |
| `llamacpp` | 166 |
| `vllm` | 104 |
| `jupyter` | 98 |
| `litellm` | 95 |
| `hfhub` | 81 |
| `docker` | 69 |
| `ollama` | 48 |
| `ray` | 13 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 957 |
| `345gs5662d34` | 815 |
| `admin` | 556 |
| `ubuntu` | 265 |
| `user` | 143 |
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
| `345gs5662d34` | 813 |
| `3245gs5662d34` | 809 |
| `123456` | 652 |
| `123` | 417 |
| `1234` | 315 |
| `12345678` | 225 |
| `admin` | 209 |
| `12345` | 196 |
| `1` | 184 |
| `password` | 140 |
| `P@ssw0rd` | 136 |
| `admin123` | 127 |
| `000000` | 104 |
| `123456789` | 101 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1122 |
| `echo` | 956 |
| `cd` | 953 |
| `cat` | 952 |
| `crontab` | 936 |
| `lscpu` | 935 |
| `ls` | 838 |
| `free` | 837 |
| `df` | 835 |
| `top` | 835 |
| `whoami` | 834 |
| `w` | 833 |
| `INFO` | 320 |
| `canary_env` | 239 |
| `PING` | 215 |


_Generated from first-party honeypot capture. CC BY 4.0._
