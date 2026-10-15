# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2482 attackers** · **480,415 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 166 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 176 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1002 |
| `canary-aws-key` | 795 |
| `ssh-bruteforce` | 573 |
| `redis-exploit` | 472 |
| `mcp-abuse` | 193 |
| `llamacpp-abuse` | 57 |
| `litellm-key-replay` | 38 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 11 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1628 |
| `redis` | 485 |
| `mcp` | 269 |
| `llamacpp` | 159 |
| `vllm` | 99 |
| `jupyter` | 96 |
| `litellm` | 90 |
| `hfhub` | 77 |
| `docker` | 67 |
| `ollama` | 48 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 937 |
| `345gs5662d34` | 801 |
| `admin` | 545 |
| `ubuntu` | 257 |
| `user` | 135 |
| `ftpuser` | 123 |
| `test` | 120 |
| `git` | 85 |
| `administrator` | 80 |
| `postgres` | 79 |
| `deploy` | 78 |
| `guest` | 75 |
| `oracle` | 62 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 800 |
| `3245gs5662d34` | 796 |
| `123456` | 633 |
| `123` | 402 |
| `1234` | 305 |
| `12345678` | 213 |
| `admin` | 201 |
| `12345` | 189 |
| `1` | 179 |
| `password` | 139 |
| `P@ssw0rd` | 130 |
| `admin123` | 123 |
| `123456789` | 102 |
| `000000` | 101 |
| `!QAZ2wsx` | 92 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1104 |
| `echo` | 939 |
| `cd` | 938 |
| `cat` | 937 |
| `crontab` | 919 |
| `lscpu` | 918 |
| `ls` | 824 |
| `free` | 823 |
| `df` | 821 |
| `top` | 821 |
| `whoami` | 820 |
| `w` | 819 |
| `INFO` | 313 |
| `canary_env` | 231 |
| `PING` | 211 |


_Generated from first-party honeypot capture. CC BY 4.0._
