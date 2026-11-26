# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6359 attackers** · **1,380,957 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 343 |
| Used a planted canary credential | 275 |
| Seen on more than one sensor | 517 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13600 |
| `ssh-bruteforce` | 1963 |
| `ssh-exploit` | 1474 |
| `redis-exploit` | 1163 |
| `mcp-abuse` | 362 |
| `docker-abuse` | 226 |
| `llamacpp-abuse` | 225 |
| `litellm-key-replay` | 211 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3603 |
| `redis` | 1195 |
| `mcp` | 712 |
| `llamacpp` | 625 |
| `vllm` | 497 |
| `litellm` | 437 |
| `docker` | 379 |
| `jupyter` | 333 |
| `ollama` | 308 |
| `hfhub` | 267 |
| `php` | 200 |
| `ray` | 76 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1957 |
| `345gs5662d34` | 1107 |
| `admin` | 959 |
| `ubuntu` | 441 |
| `guest` | 242 |
| `ftpuser` | 236 |
| `user` | 223 |
| `test` | 175 |
| `ftp` | 151 |
| `config` | 136 |
| `deploy` | 132 |
| `git` | 126 |
| `bin` | 119 |
| `administrator` | 117 |
| `george` | 117 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1096 |
| `123456` | 1048 |
| `123` | 637 |
| `1234` | 538 |
| `admin` | 421 |
| `12345678` | 414 |
| `12345` | 358 |
| `1` | 303 |
| `admin123` | 264 |
| `P@ssw0rd` | 257 |
| `password` | 175 |
| `1111` | 153 |
| `123456789` | 152 |
| `000000` | 148 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1616 |
| `cat` | 1386 |
| `cd` | 1381 |
| `echo` | 1354 |
| `crontab` | 1321 |
| `lscpu` | 1314 |
| `ls` | 1203 |
| `free` | 1197 |
| `whoami` | 1197 |
| `df` | 1194 |
| `top` | 1193 |
| `w` | 1193 |
| `INFO` | 825 |
| `PING` | 647 |
| `canary_env` | 599 |


_Generated from first-party honeypot capture. CC BY 4.0._
