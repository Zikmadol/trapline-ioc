# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2402 attackers** · **472,009 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 161 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 971 |
| `canary-aws-key` | 792 |
| `ssh-bruteforce` | 553 |
| `redis-exploit` | 461 |
| `mcp-abuse` | 187 |
| `llamacpp-abuse` | 51 |
| `litellm-key-replay` | 36 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1576 |
| `redis` | 474 |
| `mcp` | 262 |
| `llamacpp` | 152 |
| `vllm` | 97 |
| `jupyter` | 93 |
| `litellm` | 86 |
| `hfhub` | 74 |
| `docker` | 65 |
| `ollama` | 47 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 905 |
| `345gs5662d34` | 772 |
| `admin` | 527 |
| `ubuntu` | 253 |
| `user` | 129 |
| `ftpuser` | 119 |
| `test` | 114 |
| `administrator` | 82 |
| `git` | 80 |
| `postgres` | 79 |
| `deploy` | 74 |
| `guest` | 73 |
| `oracle` | 62 |
| `admin1` | 59 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 771 |
| `3245gs5662d34` | 768 |
| `123456` | 606 |
| `123` | 383 |
| `1234` | 294 |
| `12345678` | 201 |
| `admin` | 190 |
| `12345` | 183 |
| `1` | 172 |
| `password` | 130 |
| `P@ssw0rd` | 123 |
| `admin123` | 116 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 91 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1065 |
| `cd` | 908 |
| `cat` | 906 |
| `echo` | 905 |
| `crontab` | 886 |
| `lscpu` | 885 |
| `ls` | 794 |
| `free` | 793 |
| `top` | 792 |
| `df` | 791 |
| `w` | 790 |
| `whoami` | 790 |
| `INFO` | 307 |
| `canary_env` | 223 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
