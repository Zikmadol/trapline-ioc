# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6317 attackers** · **1,372,071 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 343 |
| Used a planted canary credential | 269 |
| Seen on more than one sensor | 516 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13585 |
| `ssh-bruteforce` | 1958 |
| `ssh-exploit` | 1470 |
| `redis-exploit` | 1150 |
| `mcp-abuse` | 360 |
| `llamacpp-abuse` | 226 |
| `docker-abuse` | 222 |
| `litellm-key-replay` | 206 |
| `ollama-abuse` | 169 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 33 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3593 |
| `redis` | 1182 |
| `mcp` | 709 |
| `llamacpp` | 624 |
| `vllm` | 494 |
| `litellm` | 432 |
| `docker` | 374 |
| `jupyter` | 333 |
| `ollama` | 305 |
| `hfhub` | 265 |
| `php` | 199 |
| `ray` | 75 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1949 |
| `345gs5662d34` | 1107 |
| `admin` | 957 |
| `ubuntu` | 441 |
| `guest` | 241 |
| `ftpuser` | 235 |
| `user` | 222 |
| `test` | 175 |
| `ftp` | 149 |
| `config` | 134 |
| `deploy` | 129 |
| `git` | 126 |
| `bin` | 118 |
| `administrator` | 117 |
| `george` | 116 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1104 |
| `3245gs5662d34` | 1096 |
| `123456` | 1043 |
| `123` | 637 |
| `1234` | 533 |
| `admin` | 419 |
| `12345678` | 410 |
| `12345` | 357 |
| `1` | 303 |
| `admin123` | 264 |
| `P@ssw0rd` | 256 |
| `password` | 172 |
| `1111` | 153 |
| `123456789` | 151 |
| `000000` | 147 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1612 |
| `cat` | 1383 |
| `cd` | 1378 |
| `echo` | 1351 |
| `crontab` | 1318 |
| `lscpu` | 1311 |
| `ls` | 1200 |
| `free` | 1194 |
| `whoami` | 1194 |
| `df` | 1191 |
| `top` | 1190 |
| `w` | 1190 |
| `INFO` | 812 |
| `PING` | 635 |
| `canary_env` | 596 |


_Generated from first-party honeypot capture. CC BY 4.0._
