# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2640 attackers** · **510,066 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 174 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 189 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1053 |
| `canary-aws-key` | 927 |
| `ssh-bruteforce` | 611 |
| `redis-exploit` | 498 |
| `mcp-abuse` | 208 |
| `llamacpp-abuse` | 63 |
| `litellm-key-replay` | 42 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 29 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1723 |
| `redis` | 512 |
| `mcp` | 292 |
| `llamacpp` | 173 |
| `vllm` | 107 |
| `jupyter` | 102 |
| `litellm` | 99 |
| `hfhub` | 82 |
| `docker` | 74 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 979 |
| `345gs5662d34` | 831 |
| `admin` | 580 |
| `ubuntu` | 281 |
| `user` | 148 |
| `ftpuser` | 137 |
| `test` | 122 |
| `git` | 89 |
| `deploy` | 87 |
| `postgres` | 86 |
| `administrator` | 82 |
| `guest` | 81 |
| `oracle` | 66 |
| `admin1` | 59 |
| `ftp` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 829 |
| `3245gs5662d34` | 826 |
| `123456` | 682 |
| `123` | 438 |
| `1234` | 321 |
| `12345678` | 238 |
| `admin` | 215 |
| `12345` | 202 |
| `1` | 195 |
| `password` | 145 |
| `P@ssw0rd` | 140 |
| `admin123` | 136 |
| `000000` | 109 |
| `123456789` | 105 |
| `!QAZ2wsx` | 95 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1159 |
| `cd` | 986 |
| `cat` | 985 |
| `echo` | 976 |
| `crontab` | 955 |
| `lscpu` | 954 |
| `ls` | 856 |
| `free` | 855 |
| `df` | 853 |
| `top` | 853 |
| `whoami` | 852 |
| `w` | 851 |
| `INFO` | 330 |
| `canary_env` | 251 |
| `PING` | 224 |


_Generated from first-party honeypot capture. CC BY 4.0._
