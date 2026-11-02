# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4064 attackers** · **816,203 hostile actions** · covering 51 day(s) through 2026-11-02

| signal | count |
|---|---|
| GPU / AI-hardware probing | 212 |
| Used a planted canary credential | 79 |
| Seen on more than one sensor | 297 |
| Stage-2 hosts named in payloads | 55 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5755 |
| `ssh-exploit` | 1360 |
| `ssh-bruteforce` | 1132 |
| `redis-exploit` | 706 |
| `mcp-abuse` | 270 |
| `litellm-key-replay` | 117 |
| `llamacpp-abuse` | 92 |
| `ollama-abuse` | 86 |
| `docker-abuse` | 56 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 16 |
| `vllm-key-replay` | 16 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2587 |
| `redis` | 725 |
| `mcp` | 420 |
| `llamacpp` | 294 |
| `litellm` | 218 |
| `vllm` | 185 |
| `jupyter` | 178 |
| `ollama` | 145 |
| `docker` | 139 |
| `hfhub` | 138 |
| `php` | 77 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1603 |
| `345gs5662d34` | 1098 |
| `admin` | 769 |
| `ubuntu` | 388 |
| `user` | 188 |
| `ftpuser` | 187 |
| `test` | 146 |
| `guest` | 125 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 108 |
| `administrator` | 101 |
| `ftp` | 100 |
| `oracle` | 86 |
| `debian` | 80 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 901 |
| `123` | 586 |
| `1234` | 417 |
| `12345678` | 337 |
| `admin` | 301 |
| `1` | 264 |
| `12345` | 263 |
| `P@ssw0rd` | 196 |
| `admin123` | 189 |
| `password` | 157 |
| `123456789` | 132 |
| `000000` | 127 |
| `!QAZ2wsx` | 112 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1480 |
| `cd` | 1282 |
| `cat` | 1280 |
| `echo` | 1262 |
| `crontab` | 1237 |
| `lscpu` | 1234 |
| `ls` | 1128 |
| `free` | 1126 |
| `whoami` | 1124 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 479 |
| `canary_env` | 353 |
| `PING` | 343 |


_Generated from first-party honeypot capture. CC BY 4.0._
