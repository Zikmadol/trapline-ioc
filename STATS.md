# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2550 attackers** · **497,160 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 172 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 182 |
| Stage-2 hosts named in payloads | 36 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1021 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 592 |
| `redis-exploit` | 486 |
| `mcp-abuse` | 198 |
| `llamacpp-abuse` | 59 |
| `litellm-key-replay` | 40 |
| `docker-abuse` | 27 |
| `ollama-abuse` | 25 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1667 |
| `redis` | 500 |
| `mcp` | 279 |
| `llamacpp` | 166 |
| `vllm` | 105 |
| `jupyter` | 99 |
| `litellm` | 95 |
| `hfhub` | 81 |
| `docker` | 70 |
| `ollama` | 48 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 962 |
| `345gs5662d34` | 817 |
| `admin` | 558 |
| `ubuntu` | 269 |
| `user` | 144 |
| `ftpuser` | 130 |
| `test` | 123 |
| `git` | 86 |
| `deploy` | 86 |
| `postgres` | 83 |
| `administrator` | 80 |
| `guest` | 79 |
| `oracle` | 63 |
| `AdminGPON` | 57 |
| `admin1` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 815 |
| `3245gs5662d34` | 811 |
| `123456` | 655 |
| `123` | 417 |
| `1234` | 316 |
| `12345678` | 229 |
| `admin` | 209 |
| `12345` | 196 |
| `1` | 186 |
| `password` | 140 |
| `P@ssw0rd` | 139 |
| `admin123` | 127 |
| `000000` | 105 |
| `123456789` | 101 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1126 |
| `echo` | 959 |
| `cd` | 956 |
| `cat` | 955 |
| `crontab` | 939 |
| `lscpu` | 938 |
| `ls` | 841 |
| `free` | 840 |
| `df` | 838 |
| `top` | 838 |
| `whoami` | 837 |
| `w` | 836 |
| `INFO` | 323 |
| `canary_env` | 239 |
| `PING` | 217 |


_Generated from first-party honeypot capture. CC BY 4.0._
