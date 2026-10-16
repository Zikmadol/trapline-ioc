# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2502 attackers** · **485,291 hostile actions** · covering 34 day(s) through 2026-10-16

| signal | count |
|---|---|
| GPU / AI-hardware probing | 167 |
| Used a planted canary credential | 20 |
| Seen on more than one sensor | 178 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1005 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 581 |
| `redis-exploit` | 475 |
| `mcp-abuse` | 194 |
| `llamacpp-abuse` | 58 |
| `litellm-key-replay` | 38 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 11 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1639 |
| `redis` | 489 |
| `mcp` | 271 |
| `llamacpp` | 162 |
| `vllm` | 100 |
| `jupyter` | 96 |
| `litellm` | 91 |
| `hfhub` | 77 |
| `docker` | 69 |
| `ollama` | 48 |
| `ray` | 13 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 944 |
| `345gs5662d34` | 806 |
| `admin` | 547 |
| `ubuntu` | 258 |
| `user` | 137 |
| `ftpuser` | 125 |
| `test` | 122 |
| `git` | 85 |
| `postgres` | 81 |
| `administrator` | 80 |
| `deploy` | 80 |
| `guest` | 77 |
| `oracle` | 62 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 805 |
| `3245gs5662d34` | 801 |
| `123456` | 638 |
| `123` | 405 |
| `1234` | 309 |
| `12345678` | 214 |
| `admin` | 204 |
| `12345` | 192 |
| `1` | 183 |
| `password` | 139 |
| `P@ssw0rd` | 131 |
| `admin123` | 124 |
| `000000` | 103 |
| `123456789` | 101 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1110 |
| `echo` | 945 |
| `cd` | 943 |
| `cat` | 942 |
| `crontab` | 925 |
| `lscpu` | 924 |
| `ls` | 829 |
| `free` | 828 |
| `df` | 826 |
| `top` | 826 |
| `whoami` | 825 |
| `w` | 824 |
| `INFO` | 315 |
| `canary_env` | 233 |
| `PING` | 212 |


_Generated from first-party honeypot capture. CC BY 4.0._
