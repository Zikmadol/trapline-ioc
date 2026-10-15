# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2441 attackers** · **475,502 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 163 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 986 |
| `canary-aws-key` | 793 |
| `ssh-bruteforce` | 569 |
| `redis-exploit` | 464 |
| `mcp-abuse` | 190 |
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
| `ssh` | 1607 |
| `redis` | 477 |
| `mcp` | 266 |
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
| `root` | 922 |
| `345gs5662d34` | 787 |
| `admin` | 534 |
| `ubuntu` | 253 |
| `user` | 129 |
| `ftpuser` | 120 |
| `test` | 118 |
| `administrator` | 81 |
| `git` | 81 |
| `postgres` | 78 |
| `deploy` | 77 |
| `guest` | 74 |
| `oracle` | 62 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 786 |
| `3245gs5662d34` | 783 |
| `123456` | 617 |
| `123` | 389 |
| `1234` | 299 |
| `12345678` | 207 |
| `admin` | 196 |
| `12345` | 188 |
| `1` | 172 |
| `password` | 130 |
| `P@ssw0rd` | 127 |
| `admin123` | 122 |
| `123456789` | 102 |
| `000000` | 100 |
| `!QAZ2wsx` | 91 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1087 |
| `cd` | 924 |
| `cat` | 922 |
| `echo` | 922 |
| `crontab` | 903 |
| `lscpu` | 902 |
| `ls` | 809 |
| `free` | 808 |
| `top` | 807 |
| `df` | 806 |
| `w` | 805 |
| `whoami` | 805 |
| `INFO` | 309 |
| `canary_env` | 226 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
