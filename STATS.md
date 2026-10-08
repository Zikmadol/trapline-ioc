# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1987 attackers** · **405,278 hostile actions** · covering 26 day(s) through 2026-10-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 138 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 136 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 824 |
| `ssh-bruteforce` | 469 |
| `redis-exploit` | 368 |
| `mcp-abuse` | 140 |
| `llamacpp-abuse` | 42 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 25 |
| `canary-aws-key` | 17 |
| `docker-abuse` | 16 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 9 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1331 |
| `redis` | 379 |
| `mcp` | 194 |
| `llamacpp` | 115 |
| `vllm` | 69 |
| `jupyter` | 68 |
| `litellm` | 60 |
| `hfhub` | 55 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 774 |
| `345gs5662d34` | 665 |
| `admin` | 430 |
| `ubuntu` | 199 |
| `test` | 102 |
| `user` | 102 |
| `ftpuser` | 87 |
| `administrator` | 75 |
| `git` | 59 |
| `AdminGPON` | 57 |
| `postgres` | 56 |
| `admin1` | 56 |
| `deploy` | 55 |
| `guest` | 52 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 666 |
| `345gs5662d34` | 664 |
| `123456` | 484 |
| `123` | 295 |
| `1234` | 242 |
| `12345678` | 159 |
| `admin` | 154 |
| `12345` | 139 |
| `1` | 135 |
| `password` | 112 |
| `P@ssw0rd` | 90 |
| `000000` | 89 |
| `123456789` | 83 |
| `admin123` | 82 |
| `!QAZ2wsx` | 77 |

### Top commands run

| command | times |
|---|---|
| `uname` | 897 |
| `echo` | 775 |
| `cd` | 761 |
| `lscpu` | 759 |
| `cat` | 759 |
| `crontab` | 758 |
| `ls` | 684 |
| `top` | 683 |
| `df` | 682 |
| `free` | 682 |
| `whoami` | 681 |
| `w` | 680 |
| `INFO` | 244 |
| `canary_env` | 174 |
| `PING` | 166 |


_Generated from first-party honeypot capture. CC BY 4.0._
