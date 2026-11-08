# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**4413 attackers** · **976,226 hostile actions** · covering 57 day(s) through 2026-11-08

| signal | count |
|---|---|
| GPU / AI-hardware probing | 221 |
| Used a planted canary credential | 149 |
| Seen on more than one sensor | 334 |
| Stage-2 hosts named in payloads | 58 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 7342 |
| `ssh-exploit` | 1380 |
| `ssh-bruteforce` | 1175 |
| `redis-exploit` | 803 |
| `mcp-abuse` | 285 |
| `litellm-key-replay` | 151 |
| `ollama-abuse` | 114 |
| `llamacpp-abuse` | 103 |
| `docker-abuse` | 63 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 18 |
| `vllm-key-replay` | 18 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 2662 |
| `redis` | 829 |
| `mcp` | 470 |
| `llamacpp` | 343 |
| `litellm` | 273 |
| `jupyter` | 227 |
| `vllm` | 223 |
| `ollama` | 192 |
| `hfhub` | 169 |
| `docker` | 164 |
| `php` | 99 |
| `ray` | 40 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1638 |
| `345gs5662d34` | 1098 |
| `admin` | 800 |
| `ubuntu` | 404 |
| `ftpuser` | 196 |
| `user` | 194 |
| `test` | 150 |
| `guest` | 138 |
| `git` | 117 |
| `deploy` | 113 |
| `ftp` | 109 |
| `postgres` | 108 |
| `administrator` | 104 |
| `oracle` | 90 |
| `AdminGPON` | 85 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1096 |
| `3245gs5662d34` | 1088 |
| `123456` | 923 |
| `123` | 594 |
| `1234` | 426 |
| `12345678` | 352 |
| `admin` | 323 |
| `12345` | 271 |
| `1` | 269 |
| `P@ssw0rd` | 205 |
| `admin123` | 203 |
| `password` | 160 |
| `000000` | 133 |
| `123456789` | 132 |
| `!QAZ2wsx` | 118 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1495 |
| `cd` | 1292 |
| `cat` | 1290 |
| `echo` | 1268 |
| `crontab` | 1241 |
| `lscpu` | 1238 |
| `ls` | 1128 |
| `whoami` | 1128 |
| `free` | 1126 |
| `df` | 1123 |
| `top` | 1123 |
| `w` | 1122 |
| `INFO` | 560 |
| `PING` | 409 |
| `canary_env` | 385 |


_Generated from first-party honeypot capture. CC BY 4.0._
