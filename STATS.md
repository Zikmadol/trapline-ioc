# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3196 attackers** · **647,847 hostile actions** · covering 42 day(s) through 2026-10-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 38 |
| Seen on more than one sensor | 230 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3133 |
| `ssh-exploit` | 1220 |
| `ssh-bruteforce` | 756 |
| `redis-exploit` | 583 |
| `mcp-abuse` | 239 |
| `llamacpp-abuse` | 81 |
| `ollama-abuse` | 63 |
| `litellm-key-replay` | 55 |
| `docker-abuse` | 39 |
| `jupyter-abuse` | 35 |
| `vllm-abuse` | 13 |
| `vllm-key-replay` | 12 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2053 |
| `redis` | 598 |
| `mcp` | 350 |
| `llamacpp` | 228 |
| `jupyter` | 140 |
| `vllm` | 135 |
| `litellm` | 127 |
| `ollama` | 105 |
| `hfhub` | 102 |
| `docker` | 97 |
| `php` | 30 |
| `ray` | 22 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1204 |
| `345gs5662d34` | 977 |
| `admin` | 674 |
| `ubuntu` | 319 |
| `ftpuser` | 163 |
| `user` | 162 |
| `test` | 132 |
| `git` | 109 |
| `deploy` | 106 |
| `postgres` | 104 |
| `guest` | 101 |
| `administrator` | 93 |
| `ftp` | 76 |
| `oracle` | 75 |
| `dev` | 69 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 975 |
| `3245gs5662d34` | 968 |
| `123456` | 787 |
| `123` | 509 |
| `1234` | 373 |
| `12345678` | 289 |
| `admin` | 249 |
| `12345` | 234 |
| `1` | 232 |
| `P@ssw0rd` | 171 |
| `password` | 157 |
| `admin123` | 155 |
| `000000` | 119 |
| `123456789` | 118 |
| `!QAZ2wsx` | 103 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1328 |
| `cd` | 1145 |
| `cat` | 1144 |
| `echo` | 1129 |
| `crontab` | 1107 |
| `lscpu` | 1105 |
| `ls` | 1004 |
| `free` | 1003 |
| `df` | 1001 |
| `top` | 1001 |
| `whoami` | 1000 |
| `w` | 999 |
| `INFO` | 392 |
| `canary_env` | 298 |
| `PING` | 268 |


_Generated from first-party honeypot capture. CC BY 4.0._
