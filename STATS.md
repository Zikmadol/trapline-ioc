# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5485 attackers** · **1,195,386 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 301 |
| Used a planted canary credential | 224 |
| Seen on more than one sensor | 454 |
| Stage-2 hosts named in payloads | 60 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11031 |
| `ssh-bruteforce` | 1704 |
| `ssh-exploit` | 1420 |
| `redis-exploit` | 997 |
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
| `ssh` | 3269 |
| `redis` | 1029 |
| `mcp` | 538 |
| `llamacpp` | 430 |
| `litellm` | 335 |
| `vllm` | 329 |
| `docker` | 291 |
| `jupyter` | 277 |
| `ollama` | 263 |
| `hfhub` | 222 |
| `php` | 159 |
| `ray` | 48 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1790 |
| `345gs5662d34` | 1101 |
| `admin` | 897 |
| `ubuntu` | 422 |
| `ftpuser` | 216 |
| `user` | 214 |
| `guest` | 211 |
| `test` | 172 |
| `ftp` | 130 |
| `git` | 120 |
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
| `123456` | 979 |
| `123` | 608 |
| `1234` | 473 |
| `12345678` | 386 |
| `admin` | 373 |
| `12345` | 302 |
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
| `uname` | 1536 |
| `cat` | 1319 |
| `cd` | 1313 |
| `echo` | 1292 |
| `crontab` | 1259 |
| `lscpu` | 1256 |
| `ls` | 1147 |
| `whoami` | 1142 |
| `free` | 1140 |
| `df` | 1138 |
| `top` | 1137 |
| `w` | 1137 |
| `INFO` | 710 |
| `PING` | 543 |
| `canary_env` | 438 |


_Generated from first-party honeypot capture. CC BY 4.0._
