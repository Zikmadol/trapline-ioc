# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1892 attackers** · **387,902 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 131 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 131 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 778 |
| `ssh-bruteforce` | 455 |
| `redis-exploit` | 355 |
| `mcp-abuse` | 126 |
| `llamacpp-abuse` | 38 |
| `litellm-key-replay` | 28 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 7 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1269 |
| `redis` | 366 |
| `mcp` | 177 |
| `llamacpp` | 109 |
| `vllm` | 65 |
| `jupyter` | 64 |
| `litellm` | 58 |
| `hfhub` | 51 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 732 |
| `345gs5662d34` | 624 |
| `admin` | 405 |
| `ubuntu` | 186 |
| `user` | 96 |
| `test` | 92 |
| `ftpuser` | 84 |
| `administrator` | 76 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `git` | 51 |
| `deploy` | 51 |
| `Asalem` | 50 |
| `postgres` | 49 |
| `admin2` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 624 |
| `345gs5662d34` | 623 |
| `123456` | 451 |
| `123` | 272 |
| `1234` | 226 |
| `admin` | 146 |
| `12345678` | 146 |
| `12345` | 125 |
| `1` | 123 |
| `password` | 103 |
| `000000` | 87 |
| `P@ssw0rd` | 82 |
| `admin123` | 81 |
| `123456789` | 78 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 848 |
| `echo` | 727 |
| `cd` | 716 |
| `cat` | 714 |
| `lscpu` | 713 |
| `crontab` | 712 |
| `ls` | 642 |
| `top` | 641 |
| `df` | 640 |
| `free` | 640 |
| `whoami` | 639 |
| `w` | 638 |
| `INFO` | 238 |
| `canary_env` | 157 |
| `PING` | 157 |


_Generated from first-party honeypot capture. CC BY 4.0._
