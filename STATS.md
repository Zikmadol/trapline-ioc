# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3290 attackers** · **651,294 hostile actions** · covering 43 day(s) through 2026-10-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 190 |
| Used a planted canary credential | 38 |
| Seen on more than one sensor | 240 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3258 |
| `ssh-exploit` | 1230 |
| `ssh-bruteforce` | 824 |
| `redis-exploit` | 593 |
| `mcp-abuse` | 241 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 65 |
| `litellm-key-replay` | 55 |
| `docker-abuse` | 41 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2131 |
| `redis` | 608 |
| `mcp` | 355 |
| `llamacpp` | 230 |
| `jupyter` | 148 |
| `vllm` | 137 |
| `litellm` | 129 |
| `ollama` | 107 |
| `hfhub` | 105 |
| `docker` | 104 |
| `php` | 34 |
| `ray` | 24 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1272 |
| `345gs5662d34` | 987 |
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
| `345gs5662d34` | 985 |
| `3245gs5662d34` | 979 |
| `123456` | 796 |
| `123` | 512 |
| `1234` | 379 |
| `12345678` | 297 |
| `admin` | 257 |
| `12345` | 238 |
| `1` | 233 |
| `P@ssw0rd` | 172 |
| `admin123` | 159 |
| `password` | 153 |
| `123456789` | 120 |
| `000000` | 119 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1343 |
| `cd` | 1157 |
| `cat` | 1156 |
| `echo` | 1142 |
| `crontab` | 1118 |
| `lscpu` | 1116 |
| `ls` | 1014 |
| `free` | 1013 |
| `df` | 1011 |
| `top` | 1011 |
| `whoami` | 1010 |
| `w` | 1009 |
| `INFO` | 397 |
| `canary_env` | 300 |
| `PING` | 275 |


_Generated from first-party honeypot capture. CC BY 4.0._
