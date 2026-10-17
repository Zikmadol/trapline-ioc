# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2621 attackers** · **505,355 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 173 |
| Used a planted canary credential | 21 |
| Seen on more than one sensor | 186 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1046 |
| `canary-aws-key` | 803 |
| `ssh-bruteforce` | 607 |
| `redis-exploit` | 494 |
| `mcp-abuse` | 206 |
| `llamacpp-abuse` | 63 |
| `litellm-key-replay` | 42 |
| `ollama-abuse` | 33 |
| `docker-abuse` | 28 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 12 |
| `vllm-key-replay` | 10 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1710 |
| `redis` | 508 |
| `mcp` | 289 |
| `llamacpp` | 170 |
| `vllm` | 106 |
| `jupyter` | 101 |
| `litellm` | 98 |
| `hfhub` | 81 |
| `docker` | 72 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 973 |
| `345gs5662d34` | 827 |
| `admin` | 574 |
| `ubuntu` | 278 |
| `user` | 147 |
| `ftpuser` | 135 |
| `test` | 122 |
| `git` | 88 |
| `deploy` | 87 |
| `postgres` | 85 |
| `guest` | 81 |
| `administrator` | 80 |
| `oracle` | 66 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 825 |
| `3245gs5662d34` | 821 |
| `123456` | 674 |
| `123` | 438 |
| `1234` | 322 |
| `12345678` | 237 |
| `admin` | 214 |
| `12345` | 200 |
| `1` | 190 |
| `password` | 144 |
| `P@ssw0rd` | 140 |
| `admin123` | 136 |
| `000000` | 108 |
| `123456789` | 102 |
| `!QAZ2wsx` | 93 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1152 |
| `cd` | 979 |
| `cat` | 978 |
| `echo` | 969 |
| `crontab` | 949 |
| `lscpu` | 948 |
| `ls` | 851 |
| `free` | 850 |
| `df` | 848 |
| `top` | 848 |
| `whoami` | 847 |
| `w` | 846 |
| `INFO` | 330 |
| `canary_env` | 249 |
| `PING` | 223 |


_Generated from first-party honeypot capture. CC BY 4.0._
