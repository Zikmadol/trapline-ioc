# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2350 attackers** · **464,141 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 158 |
| Used a planted canary credential | 16 |
| Seen on more than one sensor | 170 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 957 |
| `ssh-bruteforce` | 542 |
| `redis-exploit` | 443 |
| `canary-aws-key` | 416 |
| `mcp-abuse` | 186 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 35 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1551 |
| `redis` | 456 |
| `mcp` | 256 |
| `llamacpp` | 144 |
| `vllm` | 91 |
| `jupyter` | 90 |
| `litellm` | 84 |
| `hfhub` | 71 |
| `docker` | 64 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 888 |
| `345gs5662d34` | 761 |
| `admin` | 518 |
| `ubuntu` | 250 |
| `user` | 122 |
| `test` | 115 |
| `ftpuser` | 115 |
| `postgres` | 79 |
| `git` | 79 |
| `administrator` | 78 |
| `guest` | 71 |
| `deploy` | 71 |
| `oracle` | 60 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 760 |
| `3245gs5662d34` | 757 |
| `123456` | 589 |
| `123` | 375 |
| `1234` | 290 |
| `12345678` | 198 |
| `admin` | 187 |
| `12345` | 179 |
| `1` | 166 |
| `password` | 128 |
| `P@ssw0rd` | 119 |
| `admin123` | 113 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 90 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1048 |
| `cd` | 894 |
| `cat` | 892 |
| `echo` | 892 |
| `crontab` | 873 |
| `lscpu` | 872 |
| `ls` | 783 |
| `free` | 782 |
| `top` | 781 |
| `df` | 780 |
| `w` | 779 |
| `whoami` | 779 |
| `INFO` | 296 |
| `canary_env` | 222 |
| `PING` | 198 |


_Generated from first-party honeypot capture. CC BY 4.0._
