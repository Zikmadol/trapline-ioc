# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2193 attackers** · **442,512 hostile actions** · covering 29 day(s) through 2026-10-11

| signal | count |
|---|---|
| GPU / AI-hardware probing | 149 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 153 |
| Stage-2 hosts named in payloads | 31 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 905 |
| `ssh-bruteforce` | 510 |
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
| `ssh` | 1458 |
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
| `root` | 840 |
| `345gs5662d34` | 724 |
| `admin` | 479 |
| `ubuntu` | 227 |
| `user` | 113 |
| `ftpuser` | 108 |
| `test` | 106 |
| `administrator` | 76 |
| `git` | 73 |
| `postgres` | 71 |
| `guest` | 65 |
| `deploy` | 63 |
| `admin1` | 58 |
| `oracle` | 57 |
| `AdminGPON` | 56 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 723 |
| `3245gs5662d34` | 720 |
| `123456` | 541 |
| `123` | 343 |
| `1234` | 274 |
| `12345678` | 179 |
| `admin` | 177 |
| `12345` | 173 |
| `1` | 151 |
| `password` | 116 |
| `P@ssw0rd` | 108 |
| `admin123` | 102 |
| `000000` | 97 |
| `123456789` | 89 |
| `!QAZ2wsx` | 85 |

### Top commands run

| command | times |
|---|---|
| `uname` | 988 |
| `echo` | 848 |
| `cd` | 839 |
| `cat` | 838 |
| `crontab` | 830 |
| `lscpu` | 830 |
| `ls` | 745 |
| `free` | 744 |
| `top` | 744 |
| `df` | 743 |
| `whoami` | 742 |
| `w` | 741 |
| `INFO` | 273 |
| `canary_env` | 199 |
| `PING` | 188 |


_Generated from first-party honeypot capture. CC BY 4.0._
