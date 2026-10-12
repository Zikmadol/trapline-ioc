# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2223 attackers** · **450,965 hostile actions** · covering 30 day(s) through 2026-10-12

| signal | count |
|---|---|
| GPU / AI-hardware probing | 153 |
| Used a planted canary credential | 10 |
| Seen on more than one sensor | 155 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 920 |
| `ssh-bruteforce` | 517 |
| `redis-exploit` | 414 |
| `mcp-abuse` | 167 |
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
| `ssh` | 1481 |
| `redis` | 426 |
| `mcp` | 230 |
| `llamacpp` | 130 |
| `vllm` | 85 |
| `jupyter` | 82 |
| `litellm` | 73 |
| `hfhub` | 69 |
| `docker` | 53 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 849 |
| `345gs5662d34` | 732 |
| `admin` | 486 |
| `ubuntu` | 235 |
| `user` | 123 |
| `ftpuser` | 109 |
| `test` | 108 |
| `administrator` | 77 |
| `git` | 73 |
| `postgres` | 72 |
| `guest` | 66 |
| `deploy` | 66 |
| `admin1` | 59 |
| `AdminGPON` | 57 |
| `oracle` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 731 |
| `3245gs5662d34` | 728 |
| `123456` | 555 |
| `123` | 353 |
| `1234` | 278 |
| `12345678` | 184 |
| `admin` | 178 |
| `12345` | 174 |
| `1` | 154 |
| `password` | 118 |
| `P@ssw0rd` | 110 |
| `admin123` | 105 |
| `000000` | 98 |
| `123456789` | 89 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1003 |
| `echo` | 856 |
| `cd` | 853 |
| `cat` | 852 |
| `crontab` | 838 |
| `lscpu` | 838 |
| `ls` | 752 |
| `free` | 751 |
| `top` | 751 |
| `df` | 750 |
| `whoami` | 749 |
| `w` | 748 |
| `INFO` | 274 |
| `canary_env` | 202 |
| `PING` | 189 |


_Generated from first-party honeypot capture. CC BY 4.0._
