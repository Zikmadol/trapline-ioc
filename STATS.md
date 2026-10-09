# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2017 attackers** · **411,213 hostile actions** · covering 27 day(s) through 2026-10-09

| signal | count |
|---|---|
| GPU / AI-hardware probing | 141 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 136 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 837 |
| `ssh-bruteforce` | 475 |
| `redis-exploit` | 372 |
| `mcp-abuse` | 144 |
| `llamacpp-abuse` | 42 |
| `litellm-key-replay` | 30 |
| `ollama-abuse` | 25 |
| `canary-aws-key` | 17 |
| `docker-abuse` | 16 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 9 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1350 |
| `redis` | 383 |
| `mcp` | 199 |
| `llamacpp` | 117 |
| `jupyter` | 70 |
| `vllm` | 70 |
| `litellm` | 62 |
| `hfhub` | 55 |
| `docker` | 42 |
| `ollama` | 40 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 782 |
| `345gs5662d34` | 674 |
| `admin` | 437 |
| `ubuntu` | 203 |
| `test` | 104 |
| `user` | 104 |
| `ftpuser` | 90 |
| `administrator` | 76 |
| `git` | 60 |
| `postgres` | 59 |
| `deploy` | 58 |
| `AdminGPON` | 56 |
| `admin1` | 56 |
| `guest` | 54 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 674 |
| `345gs5662d34` | 673 |
| `123456` | 493 |
| `123` | 303 |
| `1234` | 251 |
| `12345678` | 162 |
| `admin` | 159 |
| `12345` | 141 |
| `1` | 140 |
| `password` | 115 |
| `000000` | 91 |
| `P@ssw0rd` | 91 |
| `123456789` | 86 |
| `admin123` | 83 |
| `!QAZ2wsx` | 80 |

### Top commands run

| command | times |
|---|---|
| `uname` | 912 |
| `echo` | 788 |
| `crontab` | 772 |
| `lscpu` | 772 |
| `cd` | 771 |
| `cat` | 769 |
| `ls` | 694 |
| `top` | 693 |
| `df` | 692 |
| `free` | 692 |
| `whoami` | 691 |
| `w` | 690 |
| `INFO` | 248 |
| `canary_env` | 178 |
| `PING` | 168 |


_Generated from first-party honeypot capture. CC BY 4.0._
