# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2274 attackers** · **454,694 hostile actions** · covering 31 day(s) through 2026-10-13

| signal | count |
|---|---|
| GPU / AI-hardware probing | 155 |
| Used a planted canary credential | 13 |
| Seen on more than one sensor | 162 |
| Stage-2 hosts named in payloads | 32 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 930 |
| `ssh-bruteforce` | 526 |
| `redis-exploit` | 425 |
| `mcp-abuse` | 178 |
| `canary-aws-key` | 150 |
| `llamacpp-abuse` | 48 |
| `litellm-key-replay` | 33 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 7 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1502 |
| `redis` | 438 |
| `mcp` | 245 |
| `llamacpp` | 137 |
| `vllm` | 87 |
| `jupyter` | 86 |
| `litellm` | 77 |
| `hfhub` | 69 |
| `docker` | 58 |
| `ollama` | 45 |
| `ray` | 10 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 859 |
| `345gs5662d34` | 741 |
| `admin` | 494 |
| `ubuntu` | 240 |
| `user` | 124 |
| `ftpuser` | 111 |
| `test` | 108 |
| `administrator` | 79 |
| `git` | 76 |
| `postgres` | 74 |
| `guest` | 69 |
| `deploy` | 67 |
| `admin1` | 59 |
| `oracle` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 740 |
| `3245gs5662d34` | 737 |
| `123456` | 565 |
| `123` | 363 |
| `1234` | 282 |
| `12345678` | 185 |
| `admin` | 182 |
| `12345` | 178 |
| `1` | 160 |
| `password` | 119 |
| `P@ssw0rd` | 113 |
| `admin123` | 108 |
| `000000` | 98 |
| `123456789` | 93 |
| `!QAZ2wsx` | 86 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1016 |
| `echo` | 866 |
| `cd` | 865 |
| `cat` | 864 |
| `crontab` | 848 |
| `lscpu` | 848 |
| `ls` | 761 |
| `free` | 760 |
| `top` | 760 |
| `df` | 759 |
| `whoami` | 758 |
| `w` | 757 |
| `INFO` | 285 |
| `canary_env` | 214 |
| `PING` | 192 |


_Generated from first-party honeypot capture. CC BY 4.0._
