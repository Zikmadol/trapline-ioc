# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6411 attackers** · **1,388,277 hostile actions** · covering 76 day(s) through 2026-11-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 345 |
| Used a planted canary credential | 276 |
| Seen on more than one sensor | 525 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13604 |
| `ssh-bruteforce` | 1978 |
| `ssh-exploit` | 1476 |
| `redis-exploit` | 1183 |
| `mcp-abuse` | 364 |
| `docker-abuse` | 230 |
| `llamacpp-abuse` | 225 |
| `litellm-key-replay` | 219 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3621 |
| `redis` | 1215 |
| `mcp` | 716 |
| `llamacpp` | 627 |
| `vllm` | 500 |
| `litellm` | 446 |
| `docker` | 387 |
| `jupyter` | 337 |
| `ollama` | 309 |
| `hfhub` | 268 |
| `php` | 204 |
| `ray` | 76 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1970 |
| `345gs5662d34` | 1107 |
| `admin` | 961 |
| `ubuntu` | 442 |
| `guest` | 243 |
| `ftpuser` | 237 |
| `user` | 225 |
| `test` | 175 |
| `ftp` | 152 |
| `config` | 137 |
| `deploy` | 132 |
| `git` | 126 |
| `bin` | 120 |
| `administrator` | 119 |
| `george` | 118 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1097 |
| `123456` | 1049 |
| `123` | 640 |
| `1234` | 541 |
| `admin` | 422 |
| `12345678` | 415 |
| `12345` | 359 |
| `1` | 302 |
| `admin123` | 267 |
| `P@ssw0rd` | 258 |
| `password` | 176 |
| `1111` | 154 |
| `123456789` | 152 |
| `000000` | 149 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1621 |
| `cat` | 1391 |
| `cd` | 1386 |
| `echo` | 1358 |
| `crontab` | 1325 |
| `lscpu` | 1318 |
| `ls` | 1207 |
| `free` | 1201 |
| `whoami` | 1201 |
| `df` | 1198 |
| `top` | 1197 |
| `w` | 1197 |
| `INFO` | 843 |
| `PING` | 667 |
| `canary_env` | 602 |


_Generated from first-party honeypot capture. CC BY 4.0._
