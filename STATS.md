# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**1815 attackers** · **378,207 hostile actions** · covering 25 day(s) through 2026-10-07

| signal | count |
|---|---|
| GPU / AI-hardware probing | 127 |
| Used a planted canary credential | 5 |
| Seen on more than one sensor | 122 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 744 |
| `ssh-bruteforce` | 444 |
| `redis-exploit` | 341 |
| `mcp-abuse` | 116 |
| `llamacpp-abuse` | 37 |
| `litellm-key-replay` | 27 |
| `ollama-abuse` | 23 |
| `docker-abuse` | 16 |
| `canary-aws-key` | 13 |
| `jupyter-abuse` | 11 |
| `vllm-abuse` | 6 |
| `vllm-key-replay` | 4 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1220 |
| `redis` | 351 |
| `mcp` | 164 |
| `llamacpp` | 104 |
| `jupyter` | 61 |
| `vllm` | 59 |
| `litellm` | 57 |
| `hfhub` | 50 |
| `docker` | 41 |
| `ollama` | 36 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 713 |
| `345gs5662d34` | 597 |
| `admin` | 386 |
| `ubuntu` | 177 |
| `user` | 90 |
| `test` | 88 |
| `ftpuser` | 78 |
| `administrator` | 77 |
| `AdminGPON` | 56 |
| `admin1` | 55 |
| `Asalem` | 51 |
| `admin2` | 51 |
| `deploy` | 50 |
| `a` | 50 |
| `postgres` | 49 |

### Top passwords tried

| password | tries |
|---|---|
| `3245gs5662d34` | 597 |
| `345gs5662d34` | 596 |
| `123456` | 433 |
| `123` | 258 |
| `1234` | 218 |
| `12345678` | 141 |
| `admin` | 139 |
| `12345` | 116 |
| `1` | 112 |
| `password` | 98 |
| `000000` | 85 |
| `123456789` | 74 |
| `P@ssw0rd` | 74 |
| `!QAZ2wsx` | 70 |
| `admin123` | 68 |

### Top commands run

| command | times |
|---|---|
| `uname` | 809 |
| `echo` | 698 |
| `lscpu` | 684 |
| `crontab` | 683 |
| `cd` | 682 |
| `cat` | 680 |
| `ls` | 615 |
| `top` | 614 |
| `df` | 613 |
| `free` | 613 |
| `whoami` | 612 |
| `w` | 611 |
| `INFO` | 226 |
| `PING` | 151 |
| `canary_env` | 145 |


_Generated from first-party honeypot capture. CC BY 4.0._
