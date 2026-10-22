# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3056 attackers** · **610,091 hostile actions** · covering 40 day(s) through 2026-10-22

| signal | count |
|---|---|
| GPU / AI-hardware probing | 186 |
| Used a planted canary credential | 35 |
| Seen on more than one sensor | 213 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2837 |
| `ssh-exploit` | 1192 |
| `ssh-bruteforce` | 685 |
| `redis-exploit` | 564 |
| `mcp-abuse` | 235 |
| `llamacpp-abuse` | 79 |
| `ollama-abuse` | 59 |
| `litellm-key-replay` | 54 |
| `docker-abuse` | 38 |
| `jupyter-abuse` | 32 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 11 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 1952 |
| `redis` | 579 |
| `mcp` | 339 |
| `llamacpp` | 216 |
| `jupyter` | 133 |
| `vllm` | 129 |
| `litellm` | 123 |
| `ollama` | 100 |
| `hfhub` | 99 |
| `docker` | 92 |
| `ray` | 22 |
| `php` | 11 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1127 |
| `345gs5662d34` | 953 |
| `admin` | 659 |
| `ubuntu` | 311 |
| `user` | 159 |
| `ftpuser` | 157 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 97 |
| `administrator` | 93 |
| `oracle` | 72 |
| `ftp` | 70 |
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 951 |
| `3245gs5662d34` | 944 |
| `123456` | 770 |
| `123` | 506 |
| `1234` | 367 |
| `12345678` | 281 |
| `admin` | 240 |
| `12345` | 230 |
| `1` | 226 |
| `P@ssw0rd` | 166 |
| `password` | 158 |
| `admin123` | 147 |
| `000000` | 118 |
| `123456789` | 115 |
| `!QAZ2wsx` | 102 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1301 |
| `cd` | 1120 |
| `cat` | 1119 |
| `echo` | 1105 |
| `crontab` | 1083 |
| `lscpu` | 1081 |
| `ls` | 980 |
| `free` | 979 |
| `df` | 977 |
| `top` | 977 |
| `whoami` | 976 |
| `w` | 975 |
| `INFO` | 381 |
| `canary_env` | 289 |
| `PING` | 261 |


_Generated from first-party honeypot capture. CC BY 4.0._
