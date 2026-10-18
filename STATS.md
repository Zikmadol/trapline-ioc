# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2693 attackers** · **518,931 hostile actions** · covering 36 day(s) through 2026-10-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 191 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1369 |
| `ssh-exploit` | 1076 |
| `ssh-bruteforce` | 623 |
| `redis-exploit` | 506 |
| `mcp-abuse` | 212 |
| `llamacpp-abuse` | 66 |
| `litellm-key-replay` | 43 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 31 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1760 |
| `redis` | 520 |
| `mcp` | 299 |
| `llamacpp` | 178 |
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
| `admin` | 606 |
| `ubuntu` | 288 |
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
| `123456` | 703 |
| `123` | 455 |
| `1234` | 331 |
| `12345678` | 246 |
| `admin` | 221 |
| `12345` | 210 |
| `1` | 202 |
| `password` | 150 |
| `P@ssw0rd` | 146 |
| `admin123` | 139 |
| `000000` | 110 |
| `123456789` | 105 |
| `!QAZ2wsx` | 96 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1185 |
| `cd` | 1011 |
| `cat` | 1010 |
| `echo` | 998 |
| `crontab` | 977 |
| `lscpu` | 976 |
| `ls` | 878 |
| `free` | 877 |
| `df` | 875 |
| `top` | 875 |
| `whoami` | 874 |
| `w` | 873 |
| `INFO` | 338 |
| `canary_env` | 255 |
| `PING` | 230 |


_Generated from first-party honeypot capture. CC BY 4.0._
