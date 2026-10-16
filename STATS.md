# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2485 attackers** · **482,354 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 166 |
| Used a planted canary credential | 20 |
| Seen on more than one sensor | 177 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1003 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 573 |
| `redis-exploit` | 473 |
| `mcp-abuse` | 193 |
| `llamacpp-abuse` | 58 |
| `litellm-key-replay` | 38 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 11 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1629 |
| `redis` | 486 |
| `mcp` | 270 |
| `llamacpp` | 160 |
| `vllm` | 100 |
| `jupyter` | 96 |
| `litellm` | 91 |
| `hfhub` | 77 |
| `docker` | 67 |
| `ollama` | 48 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 938 |
| `345gs5662d34` | 802 |
| `admin` | 545 |
| `ubuntu` | 256 |
| `user` | 136 |
| `ftpuser` | 123 |
| `test` | 120 |
| `git` | 85 |
| `postgres` | 80 |
| `administrator` | 80 |
| `deploy` | 78 |
| `guest` | 76 |
| `oracle` | 62 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 801 |
| `3245gs5662d34` | 797 |
| `123456` | 634 |
| `123` | 402 |
| `1234` | 308 |
| `12345678` | 213 |
| `admin` | 201 |
| `12345` | 189 |
| `1` | 182 |
| `password` | 139 |
| `P@ssw0rd` | 130 |
| `admin123` | 123 |
| `123456789` | 102 |
| `000000` | 101 |
| `!QAZ2wsx` | 92 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1105 |
| `echo` | 940 |
| `cd` | 939 |
| `cat` | 938 |
| `crontab` | 920 |
| `lscpu` | 919 |
| `ls` | 825 |
| `free` | 824 |
| `df` | 822 |
| `top` | 822 |
| `whoami` | 821 |
| `w` | 820 |
| `INFO` | 314 |
| `canary_env` | 232 |
| `PING` | 211 |


_Generated from first-party honeypot capture. CC BY 4.0._
