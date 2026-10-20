# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2844 attackers** · **554,335 hostile actions** · covering 38 day(s) through 2026-10-20

| signal | count |
|---|---|
| GPU / AI-hardware probing | 180 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 198 |
| Stage-2 hosts named in payloads | 38 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2270 |
| `ssh-exploit` | 1120 |
| `ssh-bruteforce` | 647 |
| `redis-exploit` | 531 |
| `mcp-abuse` | 223 |
| `llamacpp-abuse` | 73 |
| `litellm-key-replay` | 46 |
| `ollama-abuse` | 43 |
| `docker-abuse` | 33 |
| `jupyter-abuse` | 31 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1834 |
| `redis` | 545 |
| `mcp` | 316 |
| `llamacpp` | 193 |
| `jupyter` | 126 |
| `vllm` | 117 |
| `litellm` | 111 |
| `hfhub` | 93 |
| `docker` | 82 |
| `ollama` | 74 |
| `ray` | 19 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1043 |
| `345gs5662d34` | 891 |
| `admin` | 638 |
| `ubuntu` | 302 |
| `user` | 153 |
| `ftpuser` | 151 |
| `test` | 126 |
| `postgres` | 102 |
| `git` | 102 |
| `deploy` | 97 |
| `guest` | 90 |
| `administrator` | 89 |
| `oracle` | 72 |
| `dev` | 65 |
| `ftp` | 65 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 889 |
| `3245gs5662d34` | 886 |
| `123456` | 737 |
| `123` | 489 |
| `1234` | 346 |
| `12345678` | 270 |
| `admin` | 228 |
| `12345` | 222 |
| `1` | 213 |
| `P@ssw0rd` | 157 |
| `password` | 153 |
| `admin123` | 143 |
| `000000` | 113 |
| `123456789` | 109 |
| `!QAZ2wsx` | 99 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1233 |
| `cat` | 1055 |
| `cd` | 1055 |
| `echo` | 1040 |
| `crontab` | 1018 |
| `lscpu` | 1016 |
| `ls` | 917 |
| `free` | 916 |
| `df` | 914 |
| `top` | 914 |
| `whoami` | 913 |
| `w` | 912 |
| `INFO` | 358 |
| `canary_env` | 271 |
| `PING` | 245 |


_Generated from first-party honeypot capture. CC BY 4.0._
