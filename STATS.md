# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2647 attackers** · **512,817 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 174 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 189 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1054 |
| `canary-aws-key` | 975 |
| `ssh-bruteforce` | 615 |
| `redis-exploit` | 499 |
| `mcp-abuse` | 208 |
| `llamacpp-abuse` | 64 |
| `litellm-key-replay` | 42 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 29 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1728 |
| `redis` | 513 |
| `mcp` | 292 |
| `llamacpp` | 174 |
| `vllm` | 107 |
| `jupyter` | 102 |
| `litellm` | 99 |
| `hfhub` | 83 |
| `docker` | 74 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 979 |
| `345gs5662d34` | 832 |
| `admin` | 582 |
| `ubuntu` | 281 |
| `user` | 148 |
| `ftpuser` | 138 |
| `test` | 122 |
| `git` | 89 |
| `deploy` | 87 |
| `postgres` | 86 |
| `guest` | 82 |
| `administrator` | 82 |
| `oracle` | 66 |
| `admin1` | 59 |
| `ftp` | 58 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 830 |
| `3245gs5662d34` | 829 |
| `123456` | 683 |
| `123` | 440 |
| `1234` | 322 |
| `12345678` | 239 |
| `admin` | 216 |
| `12345` | 203 |
| `1` | 195 |
| `password` | 145 |
| `P@ssw0rd` | 141 |
| `admin123` | 137 |
| `000000` | 109 |
| `123456789` | 105 |
| `!QAZ2wsx` | 95 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1160 |
| `cd` | 987 |
| `cat` | 986 |
| `echo` | 977 |
| `crontab` | 956 |
| `lscpu` | 955 |
| `ls` | 857 |
| `free` | 856 |
| `df` | 854 |
| `top` | 854 |
| `whoami` | 853 |
| `w` | 852 |
| `INFO` | 331 |
| `canary_env` | 251 |
| `PING` | 225 |


_Generated from first-party honeypot capture. CC BY 4.0._
