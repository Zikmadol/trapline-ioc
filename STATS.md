# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2066 attackers** · **418,256 hostile actions** · covering 28 day(s) through 2026-10-10

| signal | count |
|---|---|
| GPU / AI-hardware probing | 143 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 141 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 855 |
| `ssh-bruteforce` | 485 |
| `redis-exploit` | 383 |
| `mcp-abuse` | 149 |
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
| `ssh` | 1379 |
| `redis` | 395 |
| `mcp` | 206 |
| `llamacpp` | 118 |
| `jupyter` | 73 |
| `vllm` | 73 |
| `litellm` | 64 |
| `hfhub` | 58 |
| `docker` | 45 |
| `ollama` | 40 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 799 |
| `345gs5662d34` | 690 |
| `admin` | 446 |
| `ubuntu` | 210 |
| `test` | 104 |
| `user` | 104 |
| `ftpuser` | 97 |
| `administrator` | 75 |
| `git` | 66 |
| `postgres` | 60 |
| `deploy` | 59 |
| `AdminGPON` | 56 |
| `guest` | 55 |
| `admin1` | 55 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 690 |
| `345gs5662d34` | 689 |
| `123456` | 508 |
| `123` | 312 |
| `1234` | 258 |
| `12345678` | 168 |
| `admin` | 161 |
| `12345` | 158 |
| `1` | 145 |
| `password` | 114 |
| `P@ssw0rd` | 95 |
| `000000` | 93 |
| `admin123` | 90 |
| `123456789` | 84 |
| `!QAZ2wsx` | 81 |

### Top commands run

| command | times |
|---|---|
| `uname` | 932 |
| `echo` | 807 |
| `crontab` | 790 |
| `lscpu` | 790 |
| `cd` | 789 |
| `cat` | 787 |
| `ls` | 710 |
| `top` | 709 |
| `df` | 708 |
| `free` | 708 |
| `whoami` | 707 |
| `w` | 706 |
| `INFO` | 255 |
| `canary_env` | 183 |
| `PING` | 176 |


_Generated from first-party honeypot capture. CC BY 4.0._
