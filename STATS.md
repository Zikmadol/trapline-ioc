# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6394 attackers** · **1,382,619 hostile actions** · covering 75 day(s) through 2026-11-26

| signal | count |
|---|---|
| GPU / AI-hardware probing | 345 |
| Used a planted canary credential | 276 |
| Seen on more than one sensor | 523 |
| Stage-2 hosts named in payloads | 74 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13601 |
| `ssh-bruteforce` | 1974 |
| `ssh-exploit` | 1475 |
| `redis-exploit` | 1175 |
| `mcp-abuse` | 363 |
| `docker-abuse` | 230 |
| `llamacpp-abuse` | 225 |
| `litellm-key-replay` | 216 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3616 |
| `redis` | 1207 |
| `mcp` | 714 |
| `llamacpp` | 626 |
| `vllm` | 499 |
| `litellm` | 442 |
| `docker` | 387 |
| `jupyter` | 334 |
| `ollama` | 308 |
| `hfhub` | 268 |
| `php` | 202 |
| `ray` | 76 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1967 |
| `345gs5662d34` | 1107 |
| `admin` | 961 |
| `ubuntu` | 442 |
| `guest` | 243 |
| `ftpuser` | 237 |
| `user` | 225 |
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
| `123456` | 1049 |
| `123` | 639 |
| `1234` | 541 |
| `admin` | 422 |
| `12345678` | 415 |
| `12345` | 359 |
| `1` | 303 |
| `admin123` | 267 |
| `P@ssw0rd` | 258 |
| `password` | 175 |
| `1111` | 154 |
| `123456789` | 152 |
| `000000` | 148 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1620 |
| `cat` | 1390 |
| `cd` | 1385 |
| `echo` | 1357 |
| `crontab` | 1324 |
| `lscpu` | 1317 |
| `ls` | 1206 |
| `free` | 1200 |
| `whoami` | 1200 |
| `df` | 1197 |
| `top` | 1196 |
| `w` | 1196 |
| `INFO` | 836 |
| `PING` | 659 |
| `canary_env` | 600 |


_Generated from first-party honeypot capture. CC BY 4.0._
