# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2053 attackers** · **416,904 hostile actions** · covering 27 day(s) through 2026-10-09

| signal | count |
|---|---|
| GPU / AI-hardware probing | 143 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 140 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 852 |
| `ssh-bruteforce` | 482 |
| `redis-exploit` | 380 |
| `mcp-abuse` | 145 |
| `llamacpp-abuse` | 42 |
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
| `ssh` | 1373 |
| `redis` | 392 |
| `mcp` | 202 |
| `llamacpp` | 118 |
| `jupyter` | 72 |
| `vllm` | 72 |
| `litellm` | 64 |
| `hfhub` | 57 |
| `docker` | 45 |
| `ollama` | 40 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 794 |
| `345gs5662d34` | 686 |
| `admin` | 444 |
| `ubuntu` | 211 |
| `user` | 105 |
| `test` | 104 |
| `ftpuser` | 93 |
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
| `3245gs5662d34` | 686 |
| `345gs5662d34` | 685 |
| `123456` | 505 |
| `123` | 306 |
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
| `uname` | 927 |
| `echo` | 803 |
| `crontab` | 786 |
| `lscpu` | 786 |
| `cd` | 784 |
| `cat` | 782 |
| `ls` | 706 |
| `top` | 705 |
| `df` | 704 |
| `free` | 704 |
| `whoami` | 703 |
| `w` | 702 |
| `INFO` | 254 |
| `canary_env` | 179 |
| `PING` | 173 |


_Generated from first-party honeypot capture. CC BY 4.0._
