# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6040 attackers** · **1,330,698 hostile actions** · covering 72 day(s) through 2026-11-23

| signal | count |
|---|---|
| GPU / AI-hardware probing | 333 |
| Used a planted canary credential | 259 |
| Seen on more than one sensor | 504 |
| Stage-2 hosts named in payloads | 69 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13539 |
| `ssh-bruteforce` | 1911 |
| `ssh-exploit` | 1463 |
| `redis-exploit` | 1086 |
| `mcp-abuse` | 338 |
| `docker-abuse` | 214 |
| `litellm-key-replay` | 191 |
| `ollama-abuse` | 164 |
| `llamacpp-abuse` | 155 |
| `jupyter-abuse` | 53 |
| `litellm-abuse` | 40 |
| `vllm-abuse` | 29 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3531 |
| `redis` | 1118 |
| `mcp` | 610 |
| `llamacpp` | 535 |
| `vllm` | 407 |
| `litellm` | 397 |
| `docker` | 361 |
| `jupyter` | 310 |
| `ollama` | 295 |
| `hfhub` | 253 |
| `php` | 185 |
| `ray` | 60 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1911 |
| `345gs5662d34` | 1106 |
| `admin` | 942 |
| `ubuntu` | 437 |
| `guest` | 235 |
| `ftpuser` | 228 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 143 |
| `deploy` | 129 |
| `config` | 128 |
| `git` | 125 |
| `administrator` | 116 |
| `support` | 114 |
| `postgres` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1032 |
| `123` | 632 |
| `1234` | 517 |
| `admin` | 406 |
| `12345678` | 406 |
| `12345` | 348 |
| `1` | 300 |
| `admin123` | 255 |
| `P@ssw0rd` | 250 |
| `password` | 173 |
| `123456789` | 150 |
| `1111` | 147 |
| `000000` | 144 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1596 |
| `cat` | 1371 |
| `cd` | 1366 |
| `echo` | 1339 |
| `crontab` | 1306 |
| `lscpu` | 1299 |
| `ls` | 1189 |
| `free` | 1183 |
| `whoami` | 1183 |
| `df` | 1180 |
| `top` | 1179 |
| `w` | 1179 |
| `INFO` | 768 |
| `PING` | 595 |
| `canary_env` | 509 |


_Generated from first-party honeypot capture. CC BY 4.0._
