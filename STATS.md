# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2664 attackers** · **514,453 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 189 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1143 |
| `ssh-exploit` | 1058 |
| `ssh-bruteforce` | 620 |
| `redis-exploit` | 500 |
| `mcp-abuse` | 211 |
| `llamacpp-abuse` | 65 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 31 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1737 |
| `redis` | 514 |
| `mcp` | 295 |
| `llamacpp` | 176 |
| `vllm` | 107 |
| `jupyter` | 102 |
| `litellm` | 100 |
| `hfhub` | 83 |
| `docker` | 76 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 987 |
| `345gs5662d34` | 838 |
| `admin` | 588 |
| `ubuntu` | 283 |
| `user` | 148 |
| `ftpuser` | 138 |
| `test` | 123 |
| `deploy` | 90 |
| `git` | 89 |
| `postgres` | 87 |
| `guest` | 82 |
| `administrator` | 82 |
| `oracle` | 67 |
| `admin1` | 59 |
| `ftp` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 836 |
| `3245gs5662d34` | 835 |
| `123456` | 688 |
| `123` | 441 |
| `1234` | 324 |
| `12345678` | 239 |
| `admin` | 218 |
| `12345` | 203 |
| `1` | 198 |
| `password` | 144 |
| `P@ssw0rd` | 142 |
| `admin123` | 137 |
| `000000` | 109 |
| `123456789` | 105 |
| `!QAZ2wsx` | 95 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1167 |
| `cd` | 993 |
| `cat` | 992 |
| `echo` | 983 |
| `crontab` | 962 |
| `lscpu` | 961 |
| `ls` | 863 |
| `free` | 862 |
| `df` | 860 |
| `top` | 860 |
| `whoami` | 859 |
| `w` | 858 |
| `INFO` | 332 |
| `canary_env` | 254 |
| `PING` | 225 |


_Generated from first-party honeypot capture. CC BY 4.0._
