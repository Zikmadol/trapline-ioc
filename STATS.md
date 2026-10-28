# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3594 attackers** · **706,701 hostile actions** · covering 46 day(s) through 2026-10-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 195 |
| Used a planted canary credential | 41 |
| Seen on more than one sensor | 263 |
| Stage-2 hosts named in payloads | 45 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3954 |
| `ssh-exploit` | 1268 |
| `ssh-bruteforce` | 999 |
| `redis-exploit` | 636 |
| `mcp-abuse` | 253 |
| `llamacpp-abuse` | 85 |
| `ollama-abuse` | 71 |
| `litellm-key-replay` | 63 |
| `docker-abuse` | 46 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2351 |
| `redis` | 653 |
| `mcp` | 377 |
| `llamacpp` | 248 |
| `jupyter` | 159 |
| `vllm` | 154 |
| `litellm` | 144 |
| `docker` | 117 |
| `ollama` | 116 |
| `hfhub` | 113 |
| `php` | 58 |
| `ray` | 29 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1448 |
| `345gs5662d34` | 1022 |
| `admin` | 714 |
| `ubuntu` | 347 |
| `ftpuser` | 173 |
| `user` | 173 |
| `test` | 139 |
| `deploy` | 112 |
| `guest` | 111 |
| `git` | 111 |
| `postgres` | 106 |
| `administrator` | 96 |
| `ftp` | 86 |
| `oracle` | 77 |
| `AdminGPON` | 71 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1020 |
| `3245gs5662d34` | 1012 |
| `123456` | 832 |
| `123` | 520 |
| `1234` | 394 |
| `12345678` | 310 |
| `admin` | 271 |
| `1` | 248 |
| `12345` | 246 |
| `P@ssw0rd` | 181 |
| `admin123` | 166 |
| `password` | 152 |
| `123456789` | 124 |
| `000000` | 123 |
| `!QAZ2wsx` | 105 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1385 |
| `cd` | 1195 |
| `cat` | 1194 |
| `echo` | 1181 |
| `crontab` | 1155 |
| `lscpu` | 1153 |
| `ls` | 1050 |
| `free` | 1048 |
| `df` | 1045 |
| `top` | 1045 |
| `w` | 1044 |
| `whoami` | 1044 |
| `INFO` | 429 |
| `canary_env` | 319 |
| `PING` | 303 |


_Generated from first-party honeypot capture. CC BY 4.0._
