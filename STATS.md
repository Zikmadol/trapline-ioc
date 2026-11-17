# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5499 attackers** · **1,198,277 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 301 |
| Used a planted canary credential | 229 |
| Seen on more than one sensor | 455 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11036 |
| `ssh-bruteforce` | 1710 |
| `ssh-exploit` | 1422 |
| `redis-exploit` | 998 |
| `mcp-abuse` | 312 |
| `litellm-key-replay` | 178 |
| `docker-abuse` | 162 |
| `ollama-abuse` | 149 |
| `llamacpp-abuse` | 128 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3277 |
| `redis` | 1030 |
| `mcp` | 538 |
| `llamacpp` | 430 |
| `litellm` | 335 |
| `vllm` | 330 |
| `docker` | 291 |
| `jupyter` | 277 |
| `ollama` | 263 |
| `hfhub` | 222 |
| `php` | 160 |
| `ray` | 48 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1794 |
| `345gs5662d34` | 1101 |
| `admin` | 897 |
| `ubuntu` | 422 |
| `ftpuser` | 216 |
| `user` | 214 |
| `guest` | 211 |
| `test` | 172 |
| `ftp` | 130 |
| `git` | 121 |
| `deploy` | 118 |
| `postgres` | 111 |
| `config` | 109 |
| `support` | 107 |
| `administrator` | 106 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1099 |
| `3245gs5662d34` | 1091 |
| `123456` | 981 |
| `123` | 608 |
| `1234` | 473 |
| `12345678` | 386 |
| `admin` | 373 |
| `12345` | 303 |
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
| `uname` | 1538 |
| `cat` | 1321 |
| `cd` | 1315 |
| `echo` | 1294 |
| `crontab` | 1261 |
| `lscpu` | 1258 |
| `ls` | 1149 |
| `whoami` | 1144 |
| `free` | 1142 |
| `df` | 1140 |
| `top` | 1139 |
| `w` | 1139 |
| `INFO` | 711 |
| `PING` | 544 |
| `canary_env` | 438 |


_Generated from first-party honeypot capture. CC BY 4.0._
