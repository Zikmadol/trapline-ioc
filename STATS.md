# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2268 attackers** · **454,332 hostile actions** · covering 30 day(s) through 2026-10-12

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 13 |
| Seen on more than one sensor | 162 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 929 |
| `ssh-bruteforce` | 524 |
| `redis-exploit` | 424 |
| `mcp-abuse` | 177 |
| `canary-aws-key` | 137 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 33 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 23 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1499 |
| `redis` | 437 |
| `mcp` | 244 |
| `llamacpp` | 137 |
| `vllm` | 87 |
| `jupyter` | 86 |
| `litellm` | 77 |
| `hfhub` | 69 |
| `docker` | 57 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 857 |
| `345gs5662d34` | 739 |
| `admin` | 492 |
| `ubuntu` | 240 |
| `user` | 123 |
| `ftpuser` | 110 |
| `test` | 109 |
| `administrator` | 77 |
| `git` | 76 |
| `postgres` | 72 |
| `guest` | 68 |
| `deploy` | 67 |
| `admin1` | 59 |
| `oracle` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 738 |
| `3245gs5662d34` | 735 |
| `123456` | 564 |
| `123` | 363 |
| `1234` | 280 |
| `12345678` | 184 |
| `admin` | 181 |
| `12345` | 175 |
| `1` | 159 |
| `password` | 119 |
| `P@ssw0rd` | 112 |
| `admin123` | 107 |
| `000000` | 98 |
| `123456789` | 91 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1014 |
| `echo` | 864 |
| `cd` | 863 |
| `cat` | 862 |
| `crontab` | 846 |
| `lscpu` | 846 |
| `ls` | 759 |
| `free` | 758 |
| `top` | 758 |
| `df` | 757 |
| `whoami` | 756 |
| `w` | 755 |
| `INFO` | 284 |
| `canary_env` | 213 |
| `PING` | 192 |


_Generated from first-party honeypot capture. CC BY 4.0._
