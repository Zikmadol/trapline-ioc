# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5518 attackers** · **1,202,022 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 301 |
| Used a planted canary credential | 230 |
| Seen on more than one sensor | 455 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11058 |
| `ssh-bruteforce` | 1721 |
| `ssh-exploit` | 1429 |
| `redis-exploit` | 999 |
| `mcp-abuse` | 312 |
| `litellm-key-replay` | 178 |
| `docker-abuse` | 162 |
| `ollama-abuse` | 149 |
| `llamacpp-abuse` | 127 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 27 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3295 |
| `redis` | 1031 |
| `mcp` | 538 |
| `llamacpp` | 430 |
| `litellm` | 335 |
| `vllm` | 331 |
| `docker` | 291 |
| `jupyter` | 277 |
| `ollama` | 263 |
| `hfhub` | 222 |
| `php` | 160 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1800 |
| `345gs5662d34` | 1101 |
| `admin` | 897 |
| `ubuntu` | 422 |
| `ftpuser` | 216 |
| `user` | 216 |
| `guest` | 211 |
| `test` | 174 |
| `ftp` | 130 |
| `git` | 121 |
| `deploy` | 119 |
| `postgres` | 110 |
| `config` | 109 |
| `administrator` | 107 |
| `support` | 107 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1099 |
| `3245gs5662d34` | 1091 |
| `123456` | 984 |
| `123` | 611 |
| `1234` | 477 |
| `12345678` | 386 |
| `admin` | 373 |
| `12345` | 307 |
| `1` | 279 |
| `admin123` | 234 |
| `P@ssw0rd` | 233 |
| `password` | 173 |
| `123456789` | 144 |
| `000000` | 138 |
| `1111` | 129 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1545 |
| `cat` | 1328 |
| `cd` | 1322 |
| `echo` | 1302 |
| `crontab` | 1268 |
| `lscpu` | 1265 |
| `ls` | 1156 |
| `whoami` | 1151 |
| `free` | 1149 |
| `df` | 1147 |
| `top` | 1146 |
| `w` | 1146 |
| `INFO` | 712 |
| `PING` | 544 |
| `canary_env` | 438 |


_Generated from first-party honeypot capture. CC BY 4.0._
