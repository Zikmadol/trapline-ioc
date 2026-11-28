# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6588 attackers** · **1,410,856 hostile actions** · covering 77 day(s) through 2026-11-28

| signal | count |
|---|---|
| GPU / AI-hardware probing | 353 |
| Used a planted canary credential | 278 |
| Seen on more than one sensor | 533 |
| Stage-2 hosts named in payloads | 76 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13615 |
| `ssh-bruteforce` | 2041 |
| `ssh-exploit` | 1497 |
| `redis-exploit` | 1238 |
| `mcp-abuse` | 365 |
| `litellm-key-replay` | 239 |
| `docker-abuse` | 235 |
| `llamacpp-abuse` | 228 |
| `ollama-abuse` | 173 |
| `jupyter-abuse` | 59 |
| `litellm-abuse` | 40 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3708 |
| `redis` | 1271 |
| `mcp` | 722 |
| `llamacpp` | 641 |
| `vllm` | 509 |
| `litellm` | 471 |
| `docker` | 396 |
| `jupyter` | 345 |
| `ollama` | 318 |
| `hfhub` | 276 |
| `php` | 213 |
| `ray` | 80 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 2035 |
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
| `123456` | 1066 |
| `123` | 649 |
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
| `uname` | 1649 |
| `cat` | 1417 |
| `cd` | 1409 |
| `echo` | 1383 |
| `crontab` | 1350 |
| `lscpu` | 1342 |
| `ls` | 1231 |
| `free` | 1225 |
| `whoami` | 1223 |
| `df` | 1221 |
| `w` | 1220 |
| `top` | 1219 |
| `INFO` | 893 |
| `PING` | 716 |
| `canary_env` | 603 |


_Generated from first-party honeypot capture. CC BY 4.0._
