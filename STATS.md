# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2433 attackers** · **475,237 hostile actions** · covering 33 day(s) through 2026-10-15

| signal | count |
|---|---|
| GPU / AI-hardware probing | 163 |
| Used a planted canary credential | 19 |
| Seen on more than one sensor | 174 |
| Stage-2 hosts named in payloads | 35 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 983 |
| `canary-aws-key` | 793 |
| `ssh-bruteforce` | 564 |
| `redis-exploit` | 464 |
| `mcp-abuse` | 190 |
| `llamacpp-abuse` | 52 |
| `litellm-key-replay` | 36 |
| `ollama-abuse` | 25 |
| `docker-abuse` | 24 |
| `jupyter-abuse` | 13 |
| `vllm-abuse` | 10 |
| `vllm-key-replay` | 8 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1599 |
| `redis` | 477 |
| `mcp` | 266 |
| `llamacpp` | 153 |
| `vllm` | 97 |
| `jupyter` | 93 |
| `litellm` | 87 |
| `hfhub` | 74 |
| `docker` | 65 |
| `ollama` | 47 |
| `ray` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 914 |
| `345gs5662d34` | 783 |
| `admin` | 534 |
| `ubuntu` | 253 |
| `user` | 129 |
| `ftpuser` | 120 |
| `test` | 118 |
| `administrator` | 81 |
| `git` | 81 |
| `postgres` | 79 |
| `deploy` | 75 |
| `guest` | 74 |
| `oracle` | 62 |
| `admin1` | 58 |
| `AdminGPON` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 782 |
| `3245gs5662d34` | 779 |
| `123456` | 617 |
| `123` | 387 |
| `1234` | 299 |
| `12345678` | 205 |
| `admin` | 195 |
| `12345` | 188 |
| `1` | 172 |
| `password` | 130 |
| `P@ssw0rd` | 127 |
| `admin123` | 122 |
| `123456789` | 101 |
| `000000` | 100 |
| `!QAZ2wsx` | 91 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1082 |
| `cd` | 920 |
| `cat` | 918 |
| `echo` | 918 |
| `crontab` | 899 |
| `lscpu` | 898 |
| `ls` | 805 |
| `free` | 804 |
| `top` | 803 |
| `df` | 802 |
| `w` | 801 |
| `whoami` | 801 |
| `INFO` | 309 |
| `canary_env` | 226 |
| `PING` | 206 |


_Generated from first-party honeypot capture. CC BY 4.0._
