# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3436 attackers** · **671,937 hostile actions** · covering 44 day(s) through 2026-10-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 193 |
| Used a planted canary credential | 40 |
| Seen on more than one sensor | 252 |
| Stage-2 hosts named in payloads | 44 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3483 |
| `ssh-exploit` | 1246 |
| `ssh-bruteforce` | 903 |
| `redis-exploit` | 618 |
| `mcp-abuse` | 246 |
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
| `ssh` | 2229 |
| `redis` | 634 |
| `mcp` | 363 |
| `llamacpp` | 238 |
| `jupyter` | 153 |
| `vllm` | 144 |
| `litellm` | 138 |
| `ollama` | 112 |
| `docker` | 111 |
| `hfhub` | 109 |
| `php` | 48 |
| `ray` | 26 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1362 |
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
| `administrator` | 95 |
| `ftp` | 81 |
| `oracle` | 76 |
| `AdminGPON` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 999 |
| `3245gs5662d34` | 991 |
| `123456` | 815 |
| `123` | 514 |
| `1234` | 387 |
| `12345678` | 304 |
| `admin` | 268 |
| `12345` | 242 |
| `1` | 240 |
| `P@ssw0rd` | 177 |
| `admin123` | 163 |
| `password` | 153 |
| `000000` | 122 |
| `123456789` | 121 |
| `!QAZ2wsx` | 104 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1362 |
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
| `INFO` | 415 |
| `canary_env` | 310 |
| `PING` | 290 |


_Generated from first-party honeypot capture. CC BY 4.0._
