# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2353 attackers** · **464,759 hostile actions** · covering 32 day(s) through 2026-10-14

| signal | count |
|---|---|
| GPU / AI-hardware probing | 158 |
| Used a planted canary credential | 16 |
| Seen on more than one sensor | 170 |
| Stage-2 hosts named in payloads | 34 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 960 |
| `ssh-bruteforce` | 542 |
| `canary-aws-key` | 449 |
| `redis-exploit` | 443 |
| `mcp-abuse` | 186 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 35 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1554 |
| `redis` | 456 |
| `mcp` | 256 |
| `llamacpp` | 144 |
| `vllm` | 91 |
| `jupyter` | 90 |
| `litellm` | 84 |
| `hfhub` | 71 |
| `docker` | 64 |
| `ollama` | 45 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 890 |
| `345gs5662d34` | 764 |
| `admin` | 518 |
| `ubuntu` | 251 |
| `user` | 123 |
| `test` | 115 |
| `ftpuser` | 115 |
| `postgres` | 79 |
| `git` | 79 |
| `administrator` | 78 |
| `guest` | 71 |
| `deploy` | 71 |
| `oracle` | 60 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 763 |
| `3245gs5662d34` | 760 |
| `123456` | 592 |
| `123` | 378 |
| `1234` | 290 |
| `12345678` | 198 |
| `admin` | 187 |
| `12345` | 180 |
| `1` | 166 |
| `password` | 128 |
| `P@ssw0rd` | 120 |
| `admin123` | 113 |
| `000000` | 100 |
| `123456789` | 99 |
| `!QAZ2wsx` | 90 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1051 |
| `cd` | 897 |
| `cat` | 895 |
| `echo` | 895 |
| `crontab` | 876 |
| `lscpu` | 875 |
| `ls` | 786 |
| `free` | 785 |
| `top` | 784 |
| `df` | 783 |
| `w` | 782 |
| `whoami` | 782 |
| `INFO` | 296 |
| `canary_env` | 222 |
| `PING` | 198 |


_Generated from first-party honeypot capture. CC BY 4.0._
