# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3386 attackers** · **665,209 hostile actions** · covering 44 day(s) through 2026-10-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 192 |
| Used a planted canary credential | 39 |
| Seen on more than one sensor | 249 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3420 |
| `ssh-exploit` | 1244 |
| `ssh-bruteforce` | 877 |
| `redis-exploit` | 609 |
| `mcp-abuse` | 244 |
| `llamacpp-abuse` | 83 |
| `ollama-abuse` | 65 |
| `litellm-key-replay` | 58 |
| `docker-abuse` | 44 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2199 |
| `redis` | 625 |
| `mcp` | 360 |
| `llamacpp` | 233 |
| `jupyter` | 150 |
| `vllm` | 141 |
| `litellm` | 134 |
| `docker` | 110 |
| `ollama` | 108 |
| `hfhub` | 107 |
| `php` | 45 |
| `ray` | 24 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1335 |
| `345gs5662d34` | 1000 |
| `admin` | 694 |
| `ubuntu` | 333 |
| `user` | 168 |
| `ftpuser` | 167 |
| `test` | 137 |
| `git` | 111 |
| `deploy` | 110 |
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
| `123456` | 810 |
| `123` | 514 |
| `1234` | 385 |
| `12345678` | 303 |
| `admin` | 264 |
| `12345` | 241 |
| `1` | 239 |
| `P@ssw0rd` | 175 |
| `admin123` | 162 |
| `password` | 154 |
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
| `INFO` | 409 |
| `canary_env` | 307 |
| `PING` | 283 |


_Generated from first-party honeypot capture. CC BY 4.0._
