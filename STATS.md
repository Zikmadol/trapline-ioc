# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2094 attackers** · **420,600 hostile actions** · covering 28 day(s) through 2026-10-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 143 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 145 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 864 |
| `ssh-bruteforce` | 490 |
| `redis-exploit` | 391 |
| `mcp-abuse` | 154 |
| `llamacpp-abuse` | 44 |
| `litellm-key-replay` | 31 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 18 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1394 |
| `redis` | 402 |
| `mcp` | 213 |
| `llamacpp` | 122 |
| `jupyter` | 75 |
| `vllm` | 75 |
| `litellm` | 66 |
| `hfhub` | 60 |
| `docker` | 46 |
| `ollama` | 42 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 804 |
| `345gs5662d34` | 697 |
| `admin` | 454 |
| `ubuntu` | 210 |
| `test` | 105 |
| `user` | 105 |
| `ftpuser` | 98 |
| `administrator` | 75 |
| `git` | 68 |
| `postgres` | 60 |
| `deploy` | 59 |
| `guest` | 58 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `debian` | 52 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 697 |
| `345gs5662d34` | 696 |
| `123456` | 514 |
| `123` | 318 |
| `1234` | 262 |
| `12345678` | 173 |
| `admin` | 167 |
| `12345` | 160 |
| `1` | 146 |
| `password` | 113 |
| `P@ssw0rd` | 99 |
| `000000` | 93 |
| `admin123` | 93 |
| `123456789` | 88 |
| `!QAZ2wsx` | 81 |

### Top commands run

| command | times |
|---|---|
| `uname` | 942 |
| `echo` | 814 |
| `cd` | 799 |
| `crontab` | 797 |
| `lscpu` | 797 |
| `cat` | 797 |
| `ls` | 717 |
| `top` | 716 |
| `df` | 715 |
| `free` | 715 |
| `whoami` | 714 |
| `w` | 713 |
| `INFO` | 261 |
| `canary_env` | 188 |
| `PING` | 180 |


_Generated from first-party honeypot capture. CC BY 4.0._
