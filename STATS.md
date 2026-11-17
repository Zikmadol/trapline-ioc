# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5442 attackers** · **1,193,885 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 301 |
| Used a planted canary credential | 205 |
| Seen on more than one sensor | 453 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 10988 |
| `ssh-bruteforce` | 1689 |
| `ssh-exploit` | 1417 |
| `redis-exploit` | 995 |
| `mcp-abuse` | 309 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 162 |
| `ollama-abuse` | 149 |
| `llamacpp-abuse` | 127 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 25 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3250 |
| `redis` | 1027 |
| `mcp` | 535 |
| `llamacpp` | 429 |
| `litellm` | 335 |
| `vllm` | 328 |
| `docker` | 291 |
| `jupyter` | 277 |
| `ollama` | 263 |
| `hfhub` | 222 |
| `php` | 158 |
| `ray` | 48 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1785 |
| `345gs5662d34` | 1101 |
| `admin` | 896 |
| `ubuntu` | 422 |
| `ftpuser` | 216 |
| `user` | 214 |
| `guest` | 210 |
| `test` | 173 |
| `ftp` | 130 |
| `git` | 120 |
| `deploy` | 117 |
| `postgres` | 111 |
| `config` | 109 |
| `administrator` | 106 |
| `support` | 105 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1099 |
| `3245gs5662d34` | 1091 |
| `123456` | 977 |
| `123` | 608 |
| `1234` | 470 |
| `12345678` | 386 |
| `admin` | 371 |
| `12345` | 300 |
| `1` | 278 |
| `admin123` | 234 |
| `P@ssw0rd` | 233 |
| `password` | 174 |
| `123456789` | 144 |
| `000000` | 137 |
| `1111` | 129 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1532 |
| `cat` | 1316 |
| `cd` | 1310 |
| `echo` | 1289 |
| `crontab` | 1256 |
| `lscpu` | 1253 |
| `ls` | 1144 |
| `whoami` | 1139 |
| `free` | 1137 |
| `df` | 1135 |
| `top` | 1134 |
| `w` | 1134 |
| `INFO` | 709 |
| `PING` | 543 |
| `canary_env` | 434 |


_Generated from first-party honeypot capture. CC BY 4.0._
