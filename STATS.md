# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3401 attackers** · **665,621 hostile actions** · covering 44 day(s) through 2026-10-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 192 |
| Used a planted canary credential | 39 |
| Seen on more than one sensor | 250 |
| Stage-2 hosts named in payloads | 44 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3432 |
| `ssh-exploit` | 1244 |
| `ssh-bruteforce` | 883 |
| `redis-exploit` | 612 |
| `mcp-abuse` | 245 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 66 |
| `litellm-key-replay` | 59 |
| `docker-abuse` | 44 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2205 |
| `redis` | 628 |
| `mcp` | 361 |
| `llamacpp` | 234 |
| `jupyter` | 151 |
| `vllm` | 142 |
| `litellm` | 136 |
| `docker` | 110 |
| `ollama` | 109 |
| `hfhub` | 108 |
| `php` | 46 |
| `ray` | 25 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1341 |
| `345gs5662d34` | 1000 |
| `admin` | 696 |
| `ubuntu` | 334 |
| `user` | 168 |
| `ftpuser` | 167 |
| `test` | 138 |
| `git` | 111 |
| `deploy` | 111 |
| `guest` | 105 |
| `postgres` | 103 |
| `administrator` | 94 |
| `ftp` | 80 |
| `oracle` | 76 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 998 |
| `3245gs5662d34` | 990 |
| `123456` | 811 |
| `123` | 514 |
| `1234` | 385 |
| `12345678` | 303 |
| `admin` | 265 |
| `12345` | 241 |
| `1` | 239 |
| `P@ssw0rd` | 175 |
| `admin123` | 162 |
| `password` | 153 |
| `000000` | 121 |
| `123456789` | 120 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1358 |
| `cd` | 1171 |
| `cat` | 1170 |
| `echo` | 1154 |
| `crontab` | 1130 |
| `lscpu` | 1128 |
| `ls` | 1026 |
| `free` | 1025 |
| `df` | 1023 |
| `top` | 1023 |
| `whoami` | 1022 |
| `w` | 1021 |
| `INFO` | 411 |
| `canary_env` | 308 |
| `PING` | 286 |


_Generated from first-party honeypot capture. CC BY 4.0._
