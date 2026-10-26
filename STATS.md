# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3372 attackers** · **663,925 hostile actions** · covering 44 day(s) through 2026-10-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 190 |
| Used a planted canary credential | 39 |
| Seen on more than one sensor | 247 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3383 |
| `ssh-exploit` | 1243 |
| `ssh-bruteforce` | 871 |
| `redis-exploit` | 607 |
| `mcp-abuse` | 243 |
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
| `ssh` | 2191 |
| `redis` | 622 |
| `mcp` | 359 |
| `llamacpp` | 233 |
| `jupyter` | 150 |
| `vllm` | 138 |
| `litellm` | 133 |
| `ollama` | 108 |
| `hfhub` | 107 |
| `docker` | 106 |
| `php` | 42 |
| `ray` | 24 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1330 |
| `345gs5662d34` | 999 |
| `admin` | 692 |
| `ubuntu` | 332 |
| `ftpuser` | 167 |
| `user` | 166 |
| `test` | 136 |
| `git` | 110 |
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
| `345gs5662d34` | 997 |
| `3245gs5662d34` | 989 |
| `123456` | 808 |
| `123` | 514 |
| `1234` | 385 |
| `12345678` | 303 |
| `admin` | 262 |
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
| `uname` | 1357 |
| `cd` | 1170 |
| `cat` | 1169 |
| `echo` | 1153 |
| `crontab` | 1129 |
| `lscpu` | 1127 |
| `ls` | 1025 |
| `free` | 1024 |
| `df` | 1022 |
| `top` | 1022 |
| `whoami` | 1021 |
| `w` | 1020 |
| `INFO` | 407 |
| `canary_env` | 306 |
| `PING` | 282 |


_Generated from first-party honeypot capture. CC BY 4.0._
