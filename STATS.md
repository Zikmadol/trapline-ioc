# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2393 attackers** · **470,029 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 160 |
| Used a planted canary credential | 17 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 969 |
| `canary-aws-key` | 726 |
| `ssh-bruteforce` | 552 |
| `redis-exploit` | 458 |
| `mcp-abuse` | 187 |
| `llamacpp-abuse` | 51 |
| `litellm-key-replay` | 35 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1573 |
| `redis` | 471 |
| `mcp` | 262 |
| `llamacpp` | 152 |
| `vllm` | 97 |
| `jupyter` | 93 |
| `litellm` | 85 |
| `hfhub` | 74 |
| `docker` | 65 |
| `ollama` | 46 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 903 |
| `345gs5662d34` | 770 |
| `admin` | 527 |
| `ubuntu` | 253 |
| `user` | 128 |
| `ftpuser` | 119 |
| `test` | 114 |
| `administrator` | 82 |
| `git` | 80 |
| `postgres` | 79 |
| `deploy` | 74 |
| `guest` | 73 |
| `oracle` | 61 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 769 |
| `3245gs5662d34` | 766 |
| `123456` | 604 |
| `123` | 383 |
| `1234` | 293 |
| `12345678` | 201 |
| `admin` | 190 |
| `12345` | 182 |
| `1` | 171 |
| `password` | 130 |
| `P@ssw0rd` | 123 |
| `admin123` | 116 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 90 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1062 |
| `cd` | 906 |
| `cat` | 904 |
| `echo` | 902 |
| `crontab` | 883 |
| `lscpu` | 882 |
| `ls` | 792 |
| `free` | 791 |
| `top` | 790 |
| `df` | 789 |
| `w` | 788 |
| `whoami` | 788 |
| `INFO` | 305 |
| `canary_env` | 223 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
