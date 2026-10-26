# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3351 attackers** · **661,408 hostile actions** · covering 44 day(s) through 2026-10-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 190 |
| Used a planted canary credential | 39 |
| Seen on more than one sensor | 246 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3340 |
| `ssh-exploit` | 1241 |
| `ssh-bruteforce` | 855 |
| `redis-exploit` | 606 |
| `mcp-abuse` | 242 |
| `llamacpp-abuse` | 83 |
| `ollama-abuse` | 65 |
| `litellm-key-replay` | 57 |
| `docker-abuse` | 42 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2173 |
| `redis` | 621 |
| `mcp` | 357 |
| `llamacpp` | 233 |
| `jupyter` | 150 |
| `vllm` | 138 |
| `litellm` | 132 |
| `ollama` | 108 |
| `hfhub` | 107 |
| `docker` | 106 |
| `php` | 41 |
| `ray` | 24 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1313 |
| `345gs5662d34` | 997 |
| `admin` | 687 |
| `ubuntu` | 333 |
| `ftpuser` | 166 |
| `user` | 166 |
| `test` | 137 |
| `git` | 110 |
| `deploy` | 110 |
| `guest` | 104 |
| `postgres` | 104 |
| `administrator` | 94 |
| `ftp` | 79 |
| `oracle` | 75 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 995 |
| `3245gs5662d34` | 987 |
| `123456` | 806 |
| `123` | 514 |
| `1234` | 383 |
| `12345678` | 302 |
| `admin` | 259 |
| `12345` | 239 |
| `1` | 238 |
| `P@ssw0rd` | 174 |
| `admin123` | 161 |
| `password` | 154 |
| `000000` | 121 |
| `123456789` | 120 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1355 |
| `cd` | 1168 |
| `cat` | 1167 |
| `echo` | 1151 |
| `crontab` | 1127 |
| `lscpu` | 1125 |
| `ls` | 1023 |
| `free` | 1022 |
| `df` | 1020 |
| `top` | 1020 |
| `whoami` | 1019 |
| `w` | 1018 |
| `INFO` | 407 |
| `canary_env` | 304 |
| `PING` | 282 |


_Generated from first-party honeypot capture. CC BY 4.0._
