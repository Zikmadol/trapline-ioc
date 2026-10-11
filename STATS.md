# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2178 attackers** · **436,562 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 148 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 153 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 897 |
| `ssh-bruteforce` | 505 |
| `redis-exploit` | 409 |
| `mcp-abuse` | 163 |
| `llamacpp-abuse` | 46 |
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
| `ssh` | 1445 |
| `redis` | 421 |
| `mcp` | 226 |
| `llamacpp` | 129 |
| `jupyter` | 82 |
| `vllm` | 81 |
| `litellm` | 72 |
| `hfhub` | 67 |
| `docker` | 52 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 832 |
| `345gs5662d34` | 717 |
| `admin` | 474 |
| `ubuntu` | 225 |
| `user` | 111 |
| `test` | 106 |
| `ftpuser` | 105 |
| `administrator` | 76 |
| `git` | 73 |
| `postgres` | 67 |
| `guest` | 65 |
| `deploy` | 63 |
| `admin1` | 58 |
| `oracle` | 57 |
| `AdminGPON` | 56 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 716 |
| `3245gs5662d34` | 715 |
| `123456` | 534 |
| `123` | 341 |
| `1234` | 271 |
| `12345678` | 179 |
| `admin` | 177 |
| `12345` | 172 |
| `1` | 151 |
| `password` | 114 |
| `P@ssw0rd` | 106 |
| `admin123` | 102 |
| `000000` | 96 |
| `123456789` | 89 |
| `!QAZ2wsx` | 84 |

### Top commands run

| command | times |
|---|---|
| `uname` | 978 |
| `echo` | 838 |
| `cd` | 831 |
| `cat` | 829 |
| `crontab` | 821 |
| `lscpu` | 821 |
| `ls` | 737 |
| `top` | 736 |
| `df` | 735 |
| `free` | 735 |
| `whoami` | 734 |
| `w` | 733 |
| `INFO` | 272 |
| `canary_env` | 198 |
| `PING` | 187 |


_Generated from first-party honeypot capture. CC BY 4.0._
