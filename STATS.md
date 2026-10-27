# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3462 attackers** · **682,869 hostile actions** · covering 45 day(s) through 2026-10-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 193 |
| Used a planted canary credential | 40 |
| Seen on more than one sensor | 254 |
| Stage-2 hosts named in payloads | 44 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3530 |
| `ssh-exploit` | 1246 |
| `ssh-bruteforce` | 924 |
| `redis-exploit` | 619 |
| `mcp-abuse` | 249 |
| `llamacpp-abuse` | 82 |
| `ollama-abuse` | 68 |
| `litellm-key-replay` | 60 |
| `docker-abuse` | 45 |
| `jupyter-abuse` | 34 |
| `vllm-abuse` | 14 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2250 |
| `redis` | 635 |
| `mcp` | 369 |
| `llamacpp` | 240 |
| `jupyter` | 154 |
| `vllm` | 146 |
| `litellm` | 139 |
| `ollama` | 113 |
| `docker` | 111 |
| `hfhub` | 110 |
| `php` | 49 |
| `ray` | 26 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1383 |
| `345gs5662d34` | 1002 |
| `admin` | 698 |
| `ubuntu` | 336 |
| `ftpuser` | 168 |
| `user` | 168 |
| `test` | 138 |
| `git` | 111 |
| `deploy` | 111 |
| `guest` | 107 |
| `postgres` | 103 |
| `administrator` | 95 |
| `ftp` | 81 |
| `oracle` | 76 |
| `AdminGPON` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1000 |
| `3245gs5662d34` | 992 |
| `123456` | 817 |
| `123` | 514 |
| `1234` | 387 |
| `12345678` | 304 |
| `admin` | 268 |
| `12345` | 242 |
| `1` | 240 |
| `P@ssw0rd` | 177 |
| `admin123` | 163 |
| `password` | 152 |
| `123456789` | 122 |
| `000000` | 122 |
| `!QAZ2wsx` | 104 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1363 |
| `cd` | 1173 |
| `cat` | 1172 |
| `echo` | 1157 |
| `crontab` | 1133 |
| `lscpu` | 1131 |
| `ls` | 1028 |
| `free` | 1027 |
| `df` | 1025 |
| `top` | 1025 |
| `whoami` | 1024 |
| `w` | 1023 |
| `INFO` | 416 |
| `canary_env` | 313 |
| `PING` | 291 |


_Generated from first-party honeypot capture. CC BY 4.0._
