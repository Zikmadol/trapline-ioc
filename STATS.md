# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1897 attackers** · **388,181 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 132 |
| Used a planted canary credential | 7 |
| Seen on more than one sensor | 131 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 781 |
| `ssh-bruteforce` | 455 |
| `redis-exploit` | 357 |
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
| `ssh` | 1272 |
| `redis` | 368 |
| `mcp` | 178 |
| `llamacpp` | 109 |
| `jupyter` | 65 |
| `vllm` | 65 |
| `litellm` | 58 |
| `hfhub` | 51 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 733 |
| `345gs5662d34` | 625 |
| `admin` | 407 |
| `ubuntu` | 186 |
| `user` | 97 |
| `test` | 92 |
| `ftpuser` | 85 |
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
| `3245gs5662d34` | 625 |
| `345gs5662d34` | 624 |
| `123456` | 452 |
| `123` | 272 |
| `1234` | 226 |
| `12345678` | 147 |
| `admin` | 146 |
| `12345` | 125 |
| `1` | 123 |
| `password` | 103 |
| `000000` | 87 |
| `P@ssw0rd` | 82 |
| `admin123` | 82 |
| `123456789` | 78 |
| `!QAZ2wsx` | 71 |

### Top commands run

| command | times |
|---|---|
| `uname` | 851 |
| `echo` | 728 |
| `cd` | 718 |
| `cat` | 716 |
| `lscpu` | 714 |
| `crontab` | 713 |
| `ls` | 643 |
| `top` | 642 |
| `df` | 641 |
| `free` | 641 |
| `whoami` | 640 |
| `w` | 639 |
| `INFO` | 239 |
| `PING` | 158 |
| `canary_env` | 157 |


_Generated from first-party honeypot capture. CC BY 4.0._
