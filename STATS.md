# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6575 attackers** · **1,410,418 hostile actions** · covering 77 day(s) through 2026-11-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 352 |
| Used a planted canary credential | 278 |
| Seen on more than one sensor | 531 |
| Stage-2 hosts named in payloads | 75 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13615 |
| `ssh-bruteforce` | 2036 |
| `ssh-exploit` | 1494 |
| `redis-exploit` | 1237 |
| `mcp-abuse` | 365 |
| `litellm-key-replay` | 239 |
| `docker-abuse` | 234 |
| `llamacpp-abuse` | 228 |
| `ollama-abuse` | 171 |
| `jupyter-abuse` | 59 |
| `litellm-abuse` | 40 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3700 |
| `redis` | 1270 |
| `mcp` | 722 |
| `llamacpp` | 641 |
| `vllm` | 509 |
| `litellm` | 471 |
| `docker` | 395 |
| `jupyter` | 345 |
| `ollama` | 316 |
| `hfhub` | 276 |
| `php` | 210 |
| `ray` | 80 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 2027 |
| `345gs5662d34` | 1109 |
| `admin` | 971 |
| `ubuntu` | 438 |
| `guest` | 246 |
| `ftpuser` | 240 |
| `user` | 226 |
| `test` | 177 |
| `ftp` | 154 |
| `config` | 139 |
| `deploy` | 132 |
| `git` | 128 |
| `bin` | 122 |
| `administrator` | 121 |
| `george` | 120 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1105 |
| `3245gs5662d34` | 1097 |
| `123456` | 1063 |
| `123` | 648 |
| `1234` | 546 |
| `admin` | 426 |
| `12345678` | 417 |
| `12345` | 362 |
| `1` | 303 |
| `admin123` | 267 |
| `P@ssw0rd` | 259 |
| `password` | 177 |
| `1111` | 156 |
| `123456789` | 154 |
| `000000` | 150 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1646 |
| `cat` | 1414 |
| `cd` | 1407 |
| `echo` | 1381 |
| `crontab` | 1348 |
| `lscpu` | 1339 |
| `ls` | 1229 |
| `free` | 1222 |
| `whoami` | 1221 |
| `df` | 1218 |
| `w` | 1218 |
| `top` | 1217 |
| `INFO` | 892 |
| `PING` | 715 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
