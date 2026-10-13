# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2343 attackers** · **462,456 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 156 |
| Used a planted canary credential | 16 |
| Seen on more than one sensor | 169 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 953 |
| `ssh-bruteforce` | 540 |
| `redis-exploit` | 442 |
| `canary-aws-key` | 370 |
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
| `ssh` | 1545 |
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
| `root` | 886 |
| `345gs5662d34` | 759 |
| `admin` | 517 |
| `ubuntu` | 249 |
| `user` | 122 |
| `test` | 115 |
| `ftpuser` | 115 |
| `postgres` | 79 |
| `administrator` | 79 |
| `git` | 79 |
| `guest` | 71 |
| `deploy` | 70 |
| `oracle` | 60 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 758 |
| `3245gs5662d34` | 755 |
| `123456` | 587 |
| `123` | 374 |
| `1234` | 290 |
| `12345678` | 197 |
| `admin` | 185 |
| `12345` | 179 |
| `1` | 165 |
| `password` | 128 |
| `P@ssw0rd` | 119 |
| `admin123` | 112 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 89 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1043 |
| `cd` | 890 |
| `cat` | 888 |
| `echo` | 888 |
| `crontab` | 869 |
| `lscpu` | 868 |
| `ls` | 781 |
| `free` | 780 |
| `top` | 779 |
| `df` | 778 |
| `w` | 777 |
| `whoami` | 777 |
| `INFO` | 295 |
| `canary_env` | 222 |
| `PING` | 198 |


_Generated from first-party honeypot capture. CC BY 4.0._
