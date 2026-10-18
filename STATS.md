# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2687 attackers** · **518,402 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 191 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1333 |
| `ssh-exploit` | 1073 |
| `ssh-bruteforce` | 623 |
| `redis-exploit` | 504 |
| `mcp-abuse` | 212 |
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
| `ssh` | 1757 |
| `redis` | 518 |
| `mcp` | 299 |
| `llamacpp` | 177 |
| `vllm` | 108 |
| `jupyter` | 103 |
| `litellm` | 101 |
| `hfhub` | 85 |
| `docker` | 77 |
| `ollama` | 59 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1000 |
| `345gs5662d34` | 852 |
| `admin` | 602 |
| `ubuntu` | 286 |
| `user` | 149 |
| `ftpuser` | 139 |
| `test` | 123 |
| `postgres` | 93 |
| `git` | 93 |
| `deploy` | 92 |
| `guest` | 84 |
| `administrator` | 82 |
| `oracle` | 69 |
| `ftp` | 62 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 850 |
| `3245gs5662d34` | 849 |
| `123456` | 702 |
| `123` | 453 |
| `1234` | 331 |
| `12345678` | 245 |
| `admin` | 221 |
| `12345` | 209 |
| `1` | 202 |
| `password` | 150 |
| `P@ssw0rd` | 145 |
| `admin123` | 138 |
| `000000` | 110 |
| `123456789` | 105 |
| `!QAZ2wsx` | 96 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1182 |
| `cd` | 1008 |
| `cat` | 1007 |
| `echo` | 998 |
| `crontab` | 977 |
| `lscpu` | 976 |
| `ls` | 878 |
| `free` | 877 |
| `df` | 875 |
| `top` | 875 |
| `whoami` | 874 |
| `w` | 873 |
| `INFO` | 336 |
| `canary_env` | 255 |
| `PING` | 229 |


_Generated from first-party honeypot capture. CC BY 4.0._
