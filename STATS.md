# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2628 attackers** · **507,222 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 173 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 187 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1049 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 610 |
| `redis-exploit` | 495 |
| `mcp-abuse` | 206 |
| `llamacpp-abuse` | 63 |
| `litellm-key-replay` | 42 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 28 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1716 |
| `redis` | 509 |
| `mcp` | 289 |
| `llamacpp` | 171 |
| `vllm` | 106 |
| `jupyter` | 102 |
| `litellm` | 99 |
| `hfhub` | 81 |
| `docker` | 73 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 977 |
| `345gs5662d34` | 828 |
| `admin` | 574 |
| `ubuntu` | 279 |
| `user` | 148 |
| `ftpuser` | 135 |
| `test` | 122 |
| `git` | 88 |
| `deploy` | 87 |
| `postgres` | 85 |
| `guest` | 81 |
| `administrator` | 80 |
| `oracle` | 66 |
| `admin1` | 58 |
| `ftp` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 826 |
| `3245gs5662d34` | 823 |
| `123456` | 678 |
| `123` | 438 |
| `1234` | 321 |
| `12345678` | 237 |
| `admin` | 215 |
| `12345` | 202 |
| `1` | 193 |
| `password` | 144 |
| `P@ssw0rd` | 140 |
| `admin123` | 136 |
| `000000` | 108 |
| `123456789` | 105 |
| `!QAZ2wsx` | 94 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1155 |
| `cd` | 983 |
| `cat` | 982 |
| `echo` | 972 |
| `crontab` | 951 |
| `lscpu` | 950 |
| `ls` | 853 |
| `free` | 852 |
| `df` | 850 |
| `top` | 850 |
| `whoami` | 849 |
| `w` | 848 |
| `INFO` | 330 |
| `canary_env` | 249 |
| `PING` | 223 |


_Generated from first-party honeypot capture. CC BY 4.0._
