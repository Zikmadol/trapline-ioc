# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6429 attackers** · **1,394,709 hostile actions** · covering 76 day(s) through 2026-11-27

| signal | count |
|---|---|
| GPU / AI-hardware probing | 345 |
| Used a planted canary credential | 276 |
| Seen on more than one sensor | 527 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13604 |
| `ssh-bruteforce` | 1990 |
| `ssh-exploit` | 1473 |
| `redis-exploit` | 1189 |
| `mcp-abuse` | 364 |
| `docker-abuse` | 230 |
| `llamacpp-abuse` | 225 |
| `litellm-key-replay` | 222 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3630 |
| `redis` | 1221 |
| `mcp` | 716 |
| `llamacpp` | 631 |
| `vllm` | 501 |
| `litellm` | 449 |
| `docker` | 387 |
| `jupyter` | 338 |
| `ollama` | 309 |
| `hfhub` | 268 |
| `php` | 205 |
| `ray` | 78 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1978 |
| `345gs5662d34` | 1107 |
| `admin` | 962 |
| `ubuntu` | 442 |
| `guest` | 244 |
| `ftpuser` | 237 |
| `user` | 226 |
| `test` | 175 |
| `ftp` | 152 |
| `config` | 137 |
| `deploy` | 132 |
| `git` | 126 |
| `bin` | 120 |
| `administrator` | 119 |
| `george` | 118 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1097 |
| `123456` | 1050 |
| `123` | 641 |
| `1234` | 541 |
| `admin` | 421 |
| `12345678` | 415 |
| `12345` | 359 |
| `1` | 302 |
| `admin123` | 266 |
| `P@ssw0rd` | 258 |
| `password` | 175 |
| `1111` | 154 |
| `123456789` | 152 |
| `000000` | 149 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1622 |
| `cat` | 1392 |
| `cd` | 1387 |
| `echo` | 1359 |
| `crontab` | 1326 |
| `lscpu` | 1319 |
| `ls` | 1208 |
| `free` | 1202 |
| `whoami` | 1202 |
| `df` | 1199 |
| `top` | 1198 |
| `w` | 1198 |
| `INFO` | 849 |
| `PING` | 673 |
| `canary_env` | 602 |


_Generated from first-party honeypot capture. CC BY 4.0._
