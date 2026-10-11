# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2202 attackers** · **445,133 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 150 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 153 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 910 |
| `ssh-bruteforce` | 514 |
| `redis-exploit` | 410 |
| `mcp-abuse` | 164 |
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
| `ssh` | 1467 |
| `redis` | 422 |
| `mcp` | 227 |
| `llamacpp` | 129 |
| `jupyter` | 82 |
| `vllm` | 82 |
| `litellm` | 72 |
| `hfhub` | 67 |
| `docker` | 52 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 846 |
| `345gs5662d34` | 729 |
| `admin` | 481 |
| `ubuntu` | 227 |
| `user` | 117 |
| `ftpuser` | 109 |
| `test` | 106 |
| `administrator` | 77 |
| `git` | 73 |
| `postgres` | 71 |
| `guest` | 66 |
| `deploy` | 66 |
| `admin1` | 59 |
| `oracle` | 57 |
| `AdminGPON` | 56 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 728 |
| `3245gs5662d34` | 725 |
| `123456` | 548 |
| `123` | 349 |
| `1234` | 276 |
| `12345678` | 184 |
| `admin` | 178 |
| `12345` | 174 |
| `1` | 153 |
| `password` | 116 |
| `P@ssw0rd` | 109 |
| `admin123` | 103 |
| `000000` | 98 |
| `123456789` | 89 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 993 |
| `echo` | 853 |
| `cd` | 844 |
| `cat` | 842 |
| `crontab` | 835 |
| `lscpu` | 835 |
| `ls` | 749 |
| `free` | 748 |
| `top` | 748 |
| `df` | 747 |
| `whoami` | 746 |
| `w` | 745 |
| `INFO` | 273 |
| `canary_env` | 199 |
| `PING` | 188 |


_Generated from first-party honeypot capture. CC BY 4.0._
