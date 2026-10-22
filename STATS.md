# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3018 attackers** · **608,938 hostile actions** · covering 40 day(s) through 2026-10-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 185 |
| Used a planted canary credential | 34 |
| Seen on more than one sensor | 209 |
| Stage-2 hosts named in payloads | 41 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2752 |
| `ssh-exploit` | 1189 |
| `ssh-bruteforce` | 665 |
| `redis-exploit` | 558 |
| `mcp-abuse` | 234 |
| `llamacpp-abuse` | 79 |
| `ollama-abuse` | 57 |
| `litellm-key-replay` | 53 |
| `docker-abuse` | 36 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1929 |
| `redis` | 572 |
| `mcp` | 336 |
| `llamacpp` | 212 |
| `jupyter` | 132 |
| `vllm` | 127 |
| `litellm` | 122 |
| `ollama` | 98 |
| `hfhub` | 97 |
| `docker` | 89 |
| `ray` | 21 |
| `php` | 7 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1103 |
| `345gs5662d34` | 951 |
| `admin` | 656 |
| `ubuntu` | 309 |
| `user` | 158 |
| `ftpuser` | 156 |
| `test` | 132 |
| `git` | 108 |
| `deploy` | 105 |
| `postgres` | 104 |
| `guest` | 96 |
| `administrator` | 92 |
| `oracle` | 72 |
| `ftp` | 70 |
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 949 |
| `3245gs5662d34` | 943 |
| `123456` | 769 |
| `123` | 506 |
| `1234` | 365 |
| `12345678` | 281 |
| `admin` | 238 |
| `12345` | 228 |
| `1` | 225 |
| `P@ssw0rd` | 166 |
| `password` | 158 |
| `admin123` | 146 |
| `000000` | 118 |
| `123456789` | 115 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1299 |
| `cat` | 1117 |
| `cd` | 1117 |
| `echo` | 1103 |
| `crontab` | 1081 |
| `lscpu` | 1079 |
| `ls` | 978 |
| `free` | 977 |
| `df` | 975 |
| `top` | 975 |
| `whoami` | 974 |
| `w` | 973 |
| `INFO` | 377 |
| `canary_env` | 288 |
| `PING` | 257 |


_Generated from first-party honeypot capture. CC BY 4.0._
