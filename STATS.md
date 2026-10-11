# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2150 attackers** · **432,795 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 145 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 152 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 891 |
| `ssh-bruteforce` | 497 |
| `redis-exploit` | 401 |
| `mcp-abuse` | 160 |
| `llamacpp-abuse` | 45 |
| `litellm-key-replay` | 32 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 22 |
| `canary-aws-key` | 17 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1431 |
| `redis` | 413 |
| `mcp` | 221 |
| `llamacpp` | 127 |
| `jupyter` | 80 |
| `vllm` | 78 |
| `litellm` | 70 |
| `hfhub` | 66 |
| `docker` | 52 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 825 |
| `345gs5662d34` | 712 |
| `admin` | 470 |
| `ubuntu` | 225 |
| `user` | 110 |
| `test` | 105 |
| `ftpuser` | 102 |
| `administrator` | 77 |
| `git` | 69 |
| `postgres` | 66 |
| `guest` | 64 |
| `deploy` | 63 |
| `admin1` | 58 |
| `AdminGPON` | 56 |
| `oracle` | 56 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 711 |
| `345gs5662d34` | 711 |
| `123456` | 531 |
| `123` | 335 |
| `1234` | 267 |
| `12345678` | 177 |
| `admin` | 171 |
| `12345` | 167 |
| `1` | 151 |
| `password` | 114 |
| `P@ssw0rd` | 105 |
| `admin123` | 100 |
| `000000` | 96 |
| `123456789` | 89 |
| `!QAZ2wsx` | 82 |

### Top commands run

| command | times |
|---|---|
| `uname` | 969 |
| `echo` | 829 |
| `cd` | 825 |
| `cat` | 823 |
| `crontab` | 812 |
| `lscpu` | 812 |
| `ls` | 731 |
| `top` | 730 |
| `df` | 729 |
| `free` | 729 |
| `whoami` | 728 |
| `w` | 727 |
| `INFO` | 267 |
| `canary_env` | 193 |
| `PING` | 185 |


_Generated from first-party honeypot capture. CC BY 4.0._
