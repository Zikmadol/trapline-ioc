# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2170 attackers** · **435,326 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 147 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 152 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 894 |
| `ssh-bruteforce` | 502 |
| `redis-exploit` | 408 |
| `mcp-abuse` | 163 |
| `llamacpp-abuse` | 45 |
| `litellm-key-replay` | 32 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 22 |
| `canary-aws-key` | 19 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1439 |
| `redis` | 420 |
| `mcp` | 224 |
| `llamacpp` | 127 |
| `jupyter` | 81 |
| `vllm` | 79 |
| `litellm` | 71 |
| `hfhub` | 66 |
| `docker` | 52 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 829 |
| `345gs5662d34` | 715 |
| `admin` | 474 |
| `ubuntu` | 225 |
| `user` | 111 |
| `test` | 105 |
| `ftpuser` | 105 |
| `administrator` | 76 |
| `git` | 70 |
| `postgres` | 66 |
| `guest` | 65 |
| `deploy` | 63 |
| `admin1` | 58 |
| `AdminGPON` | 56 |
| `oracle` | 56 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 714 |
| `3245gs5662d34` | 713 |
| `123456` | 533 |
| `123` | 339 |
| `1234` | 270 |
| `12345678` | 179 |
| `admin` | 176 |
| `12345` | 169 |
| `1` | 151 |
| `password` | 113 |
| `P@ssw0rd` | 106 |
| `admin123` | 101 |
| `000000` | 96 |
| `123456789` | 89 |
| `!QAZ2wsx` | 83 |

### Top commands run

| command | times |
|---|---|
| `uname` | 974 |
| `echo` | 834 |
| `cd` | 828 |
| `cat` | 826 |
| `crontab` | 817 |
| `lscpu` | 817 |
| `ls` | 734 |
| `top` | 733 |
| `df` | 732 |
| `free` | 732 |
| `whoami` | 731 |
| `w` | 730 |
| `INFO` | 272 |
| `canary_env` | 197 |
| `PING` | 187 |


_Generated from first-party honeypot capture. CC BY 4.0._
