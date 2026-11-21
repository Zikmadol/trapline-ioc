# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5850 attackers** · **1,279,678 hostile actions** · covering 70 day(s) through 2026-11-21

| signal | count |
|---|---|
| GPU / AI-hardware probing | 321 |
| Used a planted canary credential | 246 |
| Seen on more than one sensor | 485 |
| Stage-2 hosts named in payloads | 67 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13508 |
| `ssh-bruteforce` | 1881 |
| `ssh-exploit` | 1456 |
| `redis-exploit` | 1050 |
| `mcp-abuse` | 326 |
| `docker-abuse` | 189 |
| `litellm-key-replay` | 186 |
| `ollama-abuse` | 158 |
| `llamacpp-abuse` | 136 |
| `jupyter-abuse` | 50 |
| `vllm-abuse` | 27 |
| `php-abuse` | 26 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3490 |
| `redis` | 1082 |
| `mcp` | 568 |
| `llamacpp` | 466 |
| `litellm` | 360 |
| `vllm` | 357 |
| `docker` | 326 |
| `jupyter` | 294 |
| `ollama` | 282 |
| `hfhub` | 238 |
| `php` | 172 |
| `ray` | 56 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1895 |
| `345gs5662d34` | 1105 |
| `admin` | 928 |
| `ubuntu` | 431 |
| `guest` | 230 |
| `ftpuser` | 224 |
| `user` | 218 |
| `test` | 172 |
| `ftp` | 138 |
| `deploy` | 126 |
| `git` | 125 |
| `config` | 123 |
| `support` | 115 |
| `postgres` | 114 |
| `administrator` | 113 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1102 |
| `3245gs5662d34` | 1094 |
| `123456` | 1018 |
| `123` | 626 |
| `1234` | 506 |
| `12345678` | 399 |
| `admin` | 395 |
| `12345` | 338 |
| `1` | 292 |
| `admin123` | 247 |
| `P@ssw0rd` | 245 |
| `password` | 171 |
| `123456789` | 148 |
| `000000` | 142 |
| `1111` | 142 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1583 |
| `cat` | 1361 |
| `cd` | 1356 |
| `echo` | 1333 |
| `crontab` | 1299 |
| `lscpu` | 1293 |
| `ls` | 1184 |
| `free` | 1178 |
| `whoami` | 1178 |
| `df` | 1175 |
| `top` | 1174 |
| `w` | 1174 |
| `INFO` | 742 |
| `PING` | 572 |
| `canary_env` | 457 |


_Generated from first-party honeypot capture. CC BY 4.0._
