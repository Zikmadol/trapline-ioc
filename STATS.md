# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2491 attackers** · **484,031 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 166 |
| Used a planted canary credential | 20 |
| Seen on more than one sensor | 177 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1004 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 575 |
| `redis-exploit` | 475 |
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
| `ssh` | 1632 |
| `redis` | 488 |
| `mcp` | 270 |
| `llamacpp` | 161 |
| `vllm` | 100 |
| `jupyter` | 96 |
| `litellm` | 91 |
| `hfhub` | 77 |
| `docker` | 67 |
| `ollama` | 48 |
| `ray` | 13 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 940 |
| `345gs5662d34` | 804 |
| `admin` | 545 |
| `ubuntu` | 256 |
| `user` | 136 |
| `ftpuser` | 124 |
| `test` | 121 |
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
| `345gs5662d34` | 803 |
| `3245gs5662d34` | 799 |
| `123456` | 635 |
| `123` | 403 |
| `1234` | 307 |
| `12345678` | 213 |
| `admin` | 201 |
| `12345` | 189 |
| `1` | 182 |
| `password` | 139 |
| `P@ssw0rd` | 130 |
| `admin123` | 123 |
| `000000` | 102 |
| `123456789` | 101 |
| `!QAZ2wsx` | 92 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1107 |
| `echo` | 942 |
| `cd` | 941 |
| `cat` | 940 |
| `crontab` | 922 |
| `lscpu` | 921 |
| `ls` | 827 |
| `free` | 826 |
| `df` | 824 |
| `top` | 824 |
| `whoami` | 823 |
| `w` | 822 |
| `INFO` | 315 |
| `canary_env` | 232 |
| `PING` | 212 |


_Generated from first-party honeypot capture. CC BY 4.0._
