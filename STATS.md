# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**3196 attackers** · **647,767 hostile actions** · covering 42 day(s) through 2026-10-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 188 |
| Used a planted canary credential | 38 |
| Seen on more than one sensor | 229 |
| Stage-2 hosts named in payloads | 42 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 3127 |
| `ssh-exploit` | 1219 |
| `ssh-bruteforce` | 757 |
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
| `mcp` | 349 |
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
| `345gs5662d34` | 976 |
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
| `345gs5662d34` | 974 |
| `3245gs5662d34` | 967 |
| `123456` | 786 |
| `123` | 509 |
| `1234` | 373 |
| `12345678` | 289 |
| `admin` | 249 |
| `12345` | 233 |
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
| `uname` | 1327 |
| `cd` | 1144 |
| `cat` | 1143 |
| `echo` | 1128 |
| `crontab` | 1106 |
| `lscpu` | 1104 |
| `ls` | 1003 |
| `free` | 1002 |
| `df` | 1000 |
| `top` | 1000 |
| `whoami` | 999 |
| `w` | 998 |
| `INFO` | 392 |
| `canary_env` | 298 |
| `PING` | 268 |


_Generated from first-party honeypot capture. CC BY 4.0._
