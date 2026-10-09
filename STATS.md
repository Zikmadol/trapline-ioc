# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2060 attackers** · **417,499 hostile actions** · covering 27 day(s) through 2026-10-09

| signal | count |
|---|---|
| GPU / AI-hardware probing | 143 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 140 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 854 |
| `ssh-bruteforce` | 483 |
| `redis-exploit` | 382 |
| `mcp-abuse` | 147 |
| `llamacpp-abuse` | 43 |
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
| `ssh` | 1376 |
| `redis` | 394 |
| `mcp` | 204 |
| `llamacpp` | 118 |
| `vllm` | 73 |
| `jupyter` | 72 |
| `litellm` | 64 |
| `hfhub` | 57 |
| `docker` | 45 |
| `ollama` | 40 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 797 |
| `345gs5662d34` | 688 |
| `admin` | 444 |
| `ubuntu` | 212 |
| `test` | 104 |
| `user` | 104 |
| `ftpuser` | 96 |
| `administrator` | 75 |
| `git` | 65 |
| `postgres` | 60 |
| `deploy` | 59 |
| `AdminGPON` | 56 |
| `guest` | 55 |
| `admin1` | 55 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 688 |
| `345gs5662d34` | 687 |
| `123456` | 505 |
| `123` | 311 |
| `1234` | 257 |
| `12345678` | 168 |
| `admin` | 161 |
| `12345` | 156 |
| `1` | 143 |
| `password` | 115 |
| `P@ssw0rd` | 94 |
| `000000` | 93 |
| `admin123` | 89 |
| `123456789` | 84 |
| `!QAZ2wsx` | 81 |

### Top commands run

| command | times |
|---|---|
| `uname` | 929 |
| `echo` | 805 |
| `crontab` | 788 |
| `lscpu` | 788 |
| `cd` | 786 |
| `cat` | 784 |
| `ls` | 708 |
| `top` | 707 |
| `df` | 706 |
| `free` | 706 |
| `whoami` | 705 |
| `w` | 704 |
| `INFO` | 255 |
| `canary_env` | 181 |
| `PING` | 175 |


_Generated from first-party honeypot capture. CC BY 4.0._
