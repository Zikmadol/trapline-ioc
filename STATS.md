# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4002 attackers** · **787,208 hostile actions** · covering 50 day(s) through 2026-11-01

| signal | count |
|---|---|
| GPU / AI-hardware probing | 209 |
| Used a planted canary credential | 63 |
| Seen on more than one sensor | 289 |
| Stage-2 hosts named in payloads | 55 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 5474 |
| `ssh-exploit` | 1353 |
| `ssh-bruteforce` | 1129 |
| `redis-exploit` | 692 |
| `mcp-abuse` | 269 |
| `litellm-key-replay` | 107 |
| `llamacpp-abuse` | 91 |
| `ollama-abuse` | 81 |
| `docker-abuse` | 54 |
| `jupyter-abuse` | 38 |
| `vllm-abuse` | 15 |
| `vllm-key-replay` | 15 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2575 |
| `redis` | 711 |
| `mcp` | 416 |
| `llamacpp` | 288 |
| `litellm` | 205 |
| `vllm` | 180 |
| `jupyter` | 177 |
| `docker` | 137 |
| `ollama` | 136 |
| `hfhub` | 136 |
| `php` | 72 |
| `ray` | 33 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1598 |
| `345gs5662d34` | 1098 |
| `admin` | 760 |
| `ubuntu` | 385 |
| `user` | 188 |
| `ftpuser` | 184 |
| `test` | 146 |
| `guest` | 123 |
| `git` | 115 |
| `deploy` | 113 |
| `postgres` | 109 |
| `administrator` | 100 |
| `ftp` | 98 |
| `oracle` | 85 |
| `debian` | 78 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 896 |
| `123` | 584 |
| `1234` | 415 |
| `12345678` | 334 |
| `admin` | 295 |
| `1` | 263 |
| `12345` | 262 |
| `P@ssw0rd` | 193 |
| `admin123` | 184 |
| `password` | 157 |
| `123456789` | 132 |
| `000000` | 125 |
| `!QAZ2wsx` | 110 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1476 |
| `cd` | 1280 |
| `cat` | 1278 |
| `echo` | 1261 |
| `crontab` | 1236 |
| `lscpu` | 1233 |
| `ls` | 1128 |
| `free` | 1126 |
| `whoami` | 1124 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 469 |
| `canary_env` | 349 |
| `PING` | 335 |


_Generated from first-party honeypot capture. CC BY 4.0._
