# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2732 attackers** · **524,437 hostile actions** · covering 37 day(s) through 2026-10-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 193 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1872 |
| `ssh-exploit` | 1092 |
| `ssh-bruteforce` | 631 |
| `redis-exploit` | 511 |
| `mcp-abuse` | 217 |
| `llamacpp-abuse` | 66 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 36 |
| `docker-abuse` | 32 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1786 |
| `redis` | 525 |
| `mcp` | 304 |
| `llamacpp` | 181 |
| `vllm` | 108 |
| `jupyter` | 105 |
| `litellm` | 102 |
| `hfhub` | 87 |
| `docker` | 79 |
| `ollama` | 62 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1019 |
| `345gs5662d34` | 867 |
| `admin` | 616 |
| `ubuntu` | 299 |
| `user` | 153 |
| `ftpuser` | 141 |
| `test` | 123 |
| `git` | 98 |
| `deploy` | 94 |
| `postgres` | 93 |
| `guest` | 85 |
| `administrator` | 83 |
| `oracle` | 71 |
| `ftp` | 63 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 865 |
| `3245gs5662d34` | 863 |
| `123456` | 716 |
| `123` | 464 |
| `1234` | 339 |
| `12345678` | 257 |
| `admin` | 223 |
| `12345` | 217 |
| `1` | 203 |
| `P@ssw0rd` | 153 |
| `password` | 152 |
| `admin123` | 140 |
| `000000` | 110 |
| `123456789` | 108 |
| `!QAZ2wsx` | 97 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1201 |
| `cat` | 1026 |
| `cd` | 1026 |
| `echo` | 1014 |
| `crontab` | 991 |
| `lscpu` | 990 |
| `ls` | 892 |
| `free` | 891 |
| `df` | 889 |
| `top` | 889 |
| `whoami` | 888 |
| `w` | 887 |
| `INFO` | 342 |
| `canary_env` | 260 |
| `PING` | 233 |


_Generated from first-party honeypot capture. CC BY 4.0._
