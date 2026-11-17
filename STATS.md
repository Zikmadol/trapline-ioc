# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5513 attackers** · **1,201,699 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 301 |
| Used a planted canary credential | 230 |
| Seen on more than one sensor | 455 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11039 |
| `ssh-bruteforce` | 1719 |
| `ssh-exploit` | 1427 |
| `redis-exploit` | 998 |
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
| `ssh` | 3291 |
| `redis` | 1030 |
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
| `root` | 1796 |
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
| `123456` | 982 |
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
| `000000` | 137 |
| `1111` | 129 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1543 |
| `cat` | 1326 |
| `cd` | 1320 |
| `echo` | 1299 |
| `crontab` | 1266 |
| `lscpu` | 1263 |
| `ls` | 1154 |
| `whoami` | 1149 |
| `free` | 1147 |
| `df` | 1145 |
| `top` | 1144 |
| `w` | 1144 |
| `INFO` | 711 |
| `PING` | 544 |
| `canary_env` | 438 |


_Generated from first-party honeypot capture. CC BY 4.0._
