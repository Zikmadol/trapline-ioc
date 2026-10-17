# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2635 attackers** · **507,654 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 173 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 188 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1051 |
| `canary-aws-key` | 856 |
| `ssh-bruteforce` | 610 |
| `redis-exploit` | 497 |
| `mcp-abuse` | 208 |
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
| `ssh` | 1719 |
| `redis` | 511 |
| `mcp` | 291 |
| `llamacpp` | 172 |
| `vllm` | 106 |
| `jupyter` | 102 |
| `litellm` | 99 |
| `hfhub` | 82 |
| `docker` | 73 |
| `ollama` | 58 |
| `ray` | 14 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 980 |
| `345gs5662d34` | 830 |
| `admin` | 579 |
| `ubuntu` | 281 |
| `user` | 148 |
| `ftpuser` | 136 |
| `test` | 122 |
| `git` | 89 |
| `deploy` | 87 |
| `postgres` | 85 |
| `guest` | 81 |
| `administrator` | 81 |
| `oracle` | 66 |
| `admin1` | 58 |
| `ftp` | 57 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 828 |
| `3245gs5662d34` | 825 |
| `123456` | 681 |
| `123` | 438 |
| `1234` | 321 |
| `12345678` | 238 |
| `admin` | 215 |
| `12345` | 202 |
| `1` | 193 |
| `password` | 145 |
| `P@ssw0rd` | 140 |
| `admin123` | 136 |
| `000000` | 108 |
| `123456789` | 105 |
| `!QAZ2wsx` | 94 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1157 |
| `cd` | 985 |
| `cat` | 984 |
| `echo` | 974 |
| `crontab` | 953 |
| `lscpu` | 952 |
| `ls` | 855 |
| `free` | 854 |
| `df` | 852 |
| `top` | 852 |
| `whoami` | 851 |
| `w` | 850 |
| `INFO` | 330 |
| `canary_env` | 251 |
| `PING` | 223 |


_Generated from first-party honeypot capture. CC BY 4.0._
