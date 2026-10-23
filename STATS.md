# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3063 attackers** · **611,237 hostile actions** · covering 41 day(s) through 2026-10-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 186 |
| Used a planted canary credential | 35 |
| Seen on more than one sensor | 214 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 2840 |
| `ssh-exploit` | 1193 |
| `ssh-bruteforce` | 690 |
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
| `ssh` | 1958 |
| `redis` | 579 |
| `mcp` | 340 |
| `llamacpp` | 217 |
| `jupyter` | 134 |
| `vllm` | 129 |
| `litellm` | 123 |
| `ollama` | 100 |
| `hfhub` | 99 |
| `docker` | 92 |
| `ray` | 22 |
| `php` | 12 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1131 |
| `345gs5662d34` | 955 |
| `admin` | 660 |
| `ubuntu` | 312 |
| `user` | 160 |
| `ftpuser` | 157 |
| `test` | 131 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 97 |
| `administrator` | 93 |
| `oracle` | 73 |
| `ftp` | 70 |
| `dev` | 67 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 953 |
| `3245gs5662d34` | 946 |
| `123456` | 770 |
| `123` | 507 |
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
| `uname` | 1303 |
| `cd` | 1122 |
| `cat` | 1121 |
| `echo` | 1107 |
| `crontab` | 1085 |
| `lscpu` | 1083 |
| `ls` | 982 |
| `free` | 981 |
| `df` | 979 |
| `top` | 979 |
| `whoami` | 978 |
| `w` | 977 |
| `INFO` | 381 |
| `canary_env` | 289 |
| `PING` | 261 |


_Generated from first-party honeypot capture. CC BY 4.0._
