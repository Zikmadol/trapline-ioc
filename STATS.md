# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2734 attackers** · **524,756 hostile actions** · covering 37 day(s) through 2026-10-19

| signal | count |
|---|---|
| GPU / AI-hardware probing | 175 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 193 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 1888 |
| `ssh-exploit` | 1093 |
| `ssh-bruteforce` | 631 |
| `redis-exploit` | 511 |
| `mcp-abuse` | 218 |
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
| `ssh` | 1787 |
| `redis` | 525 |
| `mcp` | 305 |
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
| `root` | 1020 |
| `345gs5662d34` | 868 |
| `admin` | 617 |
| `ubuntu` | 299 |
| `user` | 153 |
| `ftpuser` | 141 |
| `test` | 123 |
| `git` | 98 |
| `postgres` | 94 |
| `deploy` | 94 |
| `guest` | 85 |
| `administrator` | 83 |
| `oracle` | 71 |
| `ftp` | 63 |
| `admin1` | 59 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 866 |
| `3245gs5662d34` | 864 |
| `123456` | 717 |
| `123` | 466 |
| `1234` | 340 |
| `12345678` | 257 |
| `admin` | 223 |
| `12345` | 218 |
| `1` | 203 |
| `P@ssw0rd` | 154 |
| `password` | 152 |
| `admin123` | 140 |
| `000000` | 110 |
| `123456789` | 108 |
| `!QAZ2wsx` | 97 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1202 |
| `cat` | 1027 |
| `cd` | 1027 |
| `echo` | 1015 |
| `crontab` | 992 |
| `lscpu` | 991 |
| `ls` | 893 |
| `free` | 892 |
| `df` | 890 |
| `top` | 890 |
| `whoami` | 889 |
| `w` | 888 |
| `INFO` | 342 |
| `canary_env` | 261 |
| `PING` | 233 |


_Generated from first-party honeypot capture. CC BY 4.0._
