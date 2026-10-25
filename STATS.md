# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3319 attackers** · **657,501 hostile actions** · covering 43 day(s) through 2026-10-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 190 |
| Used a planted canary credential | 39 |
| Seen on more than one sensor | 243 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3297 |
| `ssh-exploit` | 1236 |
| `ssh-bruteforce` | 836 |
| `redis-exploit` | 601 |
| `mcp-abuse` | 241 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 65 |
| `litellm-key-replay` | 57 |
| `docker-abuse` | 42 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2149 |
| `redis` | 616 |
| `mcp` | 356 |
| `llamacpp` | 230 |
| `jupyter` | 149 |
| `vllm` | 137 |
| `litellm` | 132 |
| `ollama` | 108 |
| `hfhub` | 107 |
| `docker` | 106 |
| `php` | 34 |
| `ray` | 24 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1290 |
| `345gs5662d34` | 991 |
| `admin` | 683 |
| `ubuntu` | 324 |
| `ftpuser` | 164 |
| `user` | 163 |
| `test` | 133 |
| `git` | 109 |
| `deploy` | 109 |
| `postgres` | 104 |
| `guest` | 102 |
| `administrator` | 93 |
| `ftp` | 77 |
| `oracle` | 75 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 989 |
| `3245gs5662d34` | 982 |
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
| `000000` | 120 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1347 |
| `cd` | 1161 |
| `cat` | 1160 |
| `echo` | 1146 |
| `crontab` | 1122 |
| `lscpu` | 1120 |
| `ls` | 1018 |
| `free` | 1017 |
| `df` | 1015 |
| `top` | 1015 |
| `whoami` | 1014 |
| `w` | 1013 |
| `INFO` | 403 |
| `canary_env` | 301 |
| `PING` | 280 |


_Generated from first-party honeypot capture. CC BY 4.0._
