# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6594 attackers** · **1,411,046 hostile actions** · covering 77 day(s) through 2026-11-28

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
| `ssh-bruteforce` | 2044 |
| `ssh-exploit` | 1497 |
| `redis-exploit` | 1239 |
| `mcp-abuse` | 366 |
| `litellm-key-replay` | 240 |
| `docker-abuse` | 235 |
| `llamacpp-abuse` | 228 |
| `ollama-abuse` | 173 |
| `jupyter-abuse` | 59 |
| `litellm-abuse` | 40 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3711 |
| `redis` | 1272 |
| `mcp` | 723 |
| `llamacpp` | 641 |
| `vllm` | 509 |
| `litellm` | 472 |
| `docker` | 396 |
| `jupyter` | 346 |
| `ollama` | 318 |
| `hfhub` | 276 |
| `php` | 213 |
| `ray` | 80 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 2037 |
| `345gs5662d34` | 1109 |
| `admin` | 972 |
| `ubuntu` | 438 |
| `guest` | 247 |
| `ftpuser` | 241 |
| `user` | 226 |
| `test` | 177 |
| `ftp` | 155 |
| `config` | 140 |
| `deploy` | 132 |
| `git` | 128 |
| `bin` | 123 |
| `administrator` | 121 |
| `george` | 121 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1105 |
| `3245gs5662d34` | 1097 |
| `123456` | 1067 |
| `123` | 649 |
| `1234` | 547 |
| `admin` | 427 |
| `12345678` | 418 |
| `12345` | 363 |
| `1` | 303 |
| `admin123` | 268 |
| `P@ssw0rd` | 259 |
| `password` | 177 |
| `1111` | 157 |
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
| `INFO` | 894 |
| `PING` | 716 |
| `canary_env` | 604 |


_Generated from first-party honeypot capture. CC BY 4.0._
