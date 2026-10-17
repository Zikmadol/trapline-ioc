# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**2633 attackers** · **507,418 hostile actions** · covering 35 day(s) through 2026-10-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 173 |
| Used a planted canary credential | 22 |
| Seen on more than one sensor | 188 |
| Stage-2 hosts named in payloads | 37 |

### By category

| category | IPs |
|---|---|
| `ssh-exploit` | 1050 |
| `canary-aws-key` | 804 |
| `ssh-bruteforce` | 610 |
| `redis-exploit` | 497 |
| `mcp-abuse` | 207 |
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
| `ssh` | 1718 |
| `redis` | 511 |
| `mcp` | 290 |
| `llamacpp` | 171 |
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
| `root` | 978 |
| `345gs5662d34` | 829 |
| `admin` | 577 |
| `ubuntu` | 281 |
| `user` | 148 |
| `ftpuser` | 135 |
| `test` | 122 |
| `git` | 88 |
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
| `345gs5662d34` | 827 |
| `3245gs5662d34` | 824 |
| `123456` | 679 |
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
| `uname` | 1156 |
| `cd` | 984 |
| `cat` | 983 |
| `echo` | 973 |
| `crontab` | 952 |
| `lscpu` | 951 |
| `ls` | 854 |
| `free` | 853 |
| `df` | 851 |
| `top` | 851 |
| `whoami` | 850 |
| `w` | 849 |
| `INFO` | 330 |
| `canary_env` | 250 |
| `PING` | 223 |


_Generated from first-party honeypot capture. CC BY 4.0._
