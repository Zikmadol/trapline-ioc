# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3308 attackers** · **653,643 hostile actions** · covering 43 day(s) through 2026-10-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 190 |
| Used a planted canary credential | 39 |
| Seen on more than one sensor | 242 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3280 |
| `ssh-exploit` | 1234 |
| `ssh-bruteforce` | 828 |
| `redis-exploit` | 600 |
| `mcp-abuse` | 241 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 66 |
| `litellm-key-replay` | 57 |
| `docker-abuse` | 41 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2139 |
| `redis` | 615 |
| `mcp` | 356 |
| `llamacpp` | 230 |
| `jupyter` | 149 |
| `vllm` | 137 |
| `litellm` | 132 |
| `ollama` | 108 |
| `hfhub` | 107 |
| `docker` | 105 |
| `php` | 34 |
| `ray` | 24 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1281 |
| `345gs5662d34` | 989 |
| `admin` | 683 |
| `ubuntu` | 324 |
| `ftpuser` | 164 |
| `user` | 163 |
| `test` | 132 |
| `git` | 109 |
| `deploy` | 108 |
| `postgres` | 104 |
| `guest` | 102 |
| `administrator` | 93 |
| `ftp` | 77 |
| `oracle` | 76 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 987 |
| `3245gs5662d34` | 980 |
| `123456` | 798 |
| `123` | 512 |
| `1234` | 379 |
| `12345678` | 299 |
| `admin` | 257 |
| `12345` | 238 |
| `1` | 233 |
| `P@ssw0rd` | 173 |
| `admin123` | 159 |
| `password` | 154 |
| `123456789` | 120 |
| `000000` | 119 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1345 |
| `cd` | 1159 |
| `cat` | 1158 |
| `echo` | 1144 |
| `crontab` | 1120 |
| `lscpu` | 1118 |
| `ls` | 1016 |
| `free` | 1015 |
| `df` | 1013 |
| `top` | 1013 |
| `whoami` | 1012 |
| `w` | 1011 |
| `INFO` | 402 |
| `canary_env` | 301 |
| `PING` | 280 |


_Generated from first-party honeypot capture. CC BY 4.0._
