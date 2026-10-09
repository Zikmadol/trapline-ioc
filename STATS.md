# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1997 attackers** · **406,481 hostile actions** · covering 27 day(s) through 2026-10-09

| signal | count |
|---|---|
| GPU / AI-hardware probing | 138 |
| Used a planted canary credential | 8 |
| Seen on more than one sensor | 136 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 829 |
| `ssh-bruteforce` | 468 |
| `redis-exploit` | 371 |
| `mcp-abuse` | 142 |
| `llamacpp-abuse` | 41 |
| `litellm-key-replay` | 30 |
| `ollama-abuse` | 25 |
| `canary-aws-key` | 17 |
| `docker-abuse` | 16 |
| `jupyter-abuse` | 12 |
| `vllm-abuse` | 9 |
| `vllm-key-replay` | 6 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1335 |
| `redis` | 382 |
| `mcp` | 197 |
| `llamacpp` | 116 |
| `vllm` | 69 |
| `jupyter` | 68 |
| `litellm` | 62 |
| `hfhub` | 55 |
| `docker` | 42 |
| `ollama` | 39 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 777 |
| `345gs5662d34` | 669 |
| `admin` | 432 |
| `ubuntu` | 200 |
| `test` | 102 |
| `user` | 101 |
| `ftpuser` | 88 |
| `administrator` | 75 |
| `git` | 60 |
| `postgres` | 58 |
| `AdminGPON` | 56 |
| `admin1` | 56 |
| `deploy` | 55 |
| `guest` | 52 |
| `debian` | 51 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 670 |
| `345gs5662d34` | 668 |
| `123456` | 487 |
| `123` | 298 |
| `1234` | 244 |
| `12345678` | 159 |
| `admin` | 155 |
| `12345` | 139 |
| `1` | 135 |
| `password` | 113 |
| `P@ssw0rd` | 90 |
| `000000` | 89 |
| `123456789` | 84 |
| `admin123` | 82 |
| `!QAZ2wsx` | 77 |

### Top commands run

| command | times |
|---|---|
| `uname` | 901 |
| `echo` | 779 |
| `cd` | 765 |
| `lscpu` | 763 |
| `cat` | 763 |
| `crontab` | 762 |
| `ls` | 688 |
| `top` | 687 |
| `df` | 686 |
| `free` | 686 |
| `whoami` | 685 |
| `w` | 684 |
| `INFO` | 247 |
| `canary_env` | 176 |
| `PING` | 168 |


_Generated from first-party honeypot capture. CC BY 4.0._
