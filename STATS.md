# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3419 attackers** · **669,214 hostile actions** · covering 44 day(s) through 2026-10-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 193 |
| Used a planted canary credential | 40 |
| Seen on more than one sensor | 251 |
| Stage-2 hosts named in payloads | 44 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3449 |
| `ssh-exploit` | 1246 |
| `ssh-bruteforce` | 895 |
| `redis-exploit` | 613 |
| `mcp-abuse` | 246 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 67 |
| `litellm-key-replay` | 59 |
| `docker-abuse` | 44 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2220 |
| `redis` | 629 |
| `mcp` | 363 |
| `llamacpp` | 234 |
| `jupyter` | 152 |
| `vllm` | 142 |
| `litellm` | 137 |
| `ollama` | 111 |
| `docker` | 110 |
| `hfhub` | 108 |
| `php` | 46 |
| `ray` | 25 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1354 |
| `345gs5662d34` | 1001 |
| `admin` | 698 |
| `ubuntu` | 335 |
| `ftpuser` | 168 |
| `user` | 168 |
| `test` | 138 |
| `git` | 111 |
| `deploy` | 111 |
| `guest` | 106 |
| `postgres` | 103 |
| `administrator` | 94 |
| `ftp` | 81 |
| `oracle` | 76 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 999 |
| `3245gs5662d34` | 991 |
| `123456` | 814 |
| `123` | 514 |
| `1234` | 386 |
| `12345678` | 304 |
| `admin` | 266 |
| `12345` | 242 |
| `1` | 241 |
| `P@ssw0rd` | 177 |
| `admin123` | 163 |
| `password` | 153 |
| `000000` | 121 |
| `123456789` | 120 |
| `!QAZ2wsx` | 104 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1360 |
| `cd` | 1172 |
| `cat` | 1171 |
| `echo` | 1156 |
| `crontab` | 1132 |
| `lscpu` | 1130 |
| `ls` | 1027 |
| `free` | 1026 |
| `df` | 1024 |
| `top` | 1024 |
| `whoami` | 1023 |
| `w` | 1022 |
| `INFO` | 413 |
| `canary_env` | 310 |
| `PING` | 287 |


_Generated from first-party honeypot capture. CC BY 4.0._
