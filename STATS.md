# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2419 attackers** · **473,135 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 162 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 975 |
| `canary-aws-key` | 792 |
| `ssh-bruteforce` | 561 |
| `redis-exploit` | 463 |
| `mcp-abuse` | 188 |
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
| `ssh` | 1588 |
| `redis` | 476 |
| `mcp` | 263 |
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
| `root` | 910 |
| `345gs5662d34` | 775 |
| `admin` | 532 |
| `ubuntu` | 254 |
| `user` | 128 |
| `ftpuser` | 120 |
| `test` | 116 |
| `administrator` | 82 |
| `git` | 80 |
| `postgres` | 79 |
| `guest` | 75 |
| `deploy` | 75 |
| `oracle` | 62 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 774 |
| `3245gs5662d34` | 771 |
| `123456` | 610 |
| `123` | 384 |
| `1234` | 298 |
| `12345678` | 204 |
| `admin` | 193 |
| `12345` | 186 |
| `1` | 172 |
| `password` | 129 |
| `P@ssw0rd` | 126 |
| `admin123` | 121 |
| `123456789` | 100 |
| `000000` | 100 |
| `!QAZ2wsx` | 91 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1072 |
| `cd` | 912 |
| `cat` | 910 |
| `echo` | 909 |
| `crontab` | 890 |
| `lscpu` | 889 |
| `ls` | 797 |
| `free` | 796 |
| `top` | 795 |
| `df` | 794 |
| `w` | 793 |
| `whoami` | 793 |
| `INFO` | 309 |
| `canary_env` | 224 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
