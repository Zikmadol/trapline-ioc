# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2347 attackers** · **463,519 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 157 |
| Used a planted canary credential | 16 |
| Seen on more than one sensor | 169 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 956 |
| `ssh-bruteforce` | 541 |
| `redis-exploit` | 442 |
| `canary-aws-key` | 386 |
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
| `ssh` | 1549 |
| `redis` | 455 |
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
| `root` | 887 |
| `345gs5662d34` | 760 |
| `admin` | 518 |
| `ubuntu` | 250 |
| `user` | 122 |
| `test` | 115 |
| `ftpuser` | 115 |
| `postgres` | 79 |
| `administrator` | 79 |
| `git` | 79 |
| `guest` | 71 |
| `deploy` | 71 |
| `oracle` | 60 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 759 |
| `3245gs5662d34` | 756 |
| `123456` | 588 |
| `123` | 375 |
| `1234` | 290 |
| `12345678` | 197 |
| `admin` | 186 |
| `12345` | 179 |
| `1` | 165 |
| `password` | 128 |
| `P@ssw0rd` | 119 |
| `admin123` | 113 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 90 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1047 |
| `cd` | 893 |
| `cat` | 891 |
| `echo` | 890 |
| `crontab` | 871 |
| `lscpu` | 870 |
| `ls` | 782 |
| `free` | 781 |
| `top` | 780 |
| `df` | 779 |
| `w` | 778 |
| `whoami` | 778 |
| `INFO` | 295 |
| `canary_env` | 222 |
| `PING` | 198 |


_Generated from first-party honeypot capture. CC BY 4.0._
