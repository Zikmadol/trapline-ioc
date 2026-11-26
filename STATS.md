# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6384 attackers** · **1,382,363 hostile actions** · covering 75 day(s) through 2026-11-26

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
| `ssh-bruteforce` | 1969 |
| `ssh-exploit` | 1475 |
| `redis-exploit` | 1172 |
| `mcp-abuse` | 363 |
| `docker-abuse` | 230 |
| `llamacpp-abuse` | 225 |
| `litellm-key-replay` | 214 |
| `ollama-abuse` | 170 |
| `jupyter-abuse` | 58 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 35 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3611 |
| `redis` | 1204 |
| `mcp` | 714 |
| `llamacpp` | 626 |
| `vllm` | 499 |
| `litellm` | 440 |
| `docker` | 387 |
| `jupyter` | 334 |
| `ollama` | 308 |
| `hfhub` | 268 |
| `php` | 202 |
| `ray` | 76 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1962 |
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
| `password` | 174 |
| `1111` | 154 |
| `123456789` | 152 |
| `000000` | 148 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1619 |
| `cat` | 1389 |
| `cd` | 1384 |
| `echo` | 1356 |
| `crontab` | 1323 |
| `lscpu` | 1316 |
| `ls` | 1205 |
| `free` | 1199 |
| `whoami` | 1199 |
| `df` | 1196 |
| `top` | 1195 |
| `w` | 1195 |
| `INFO` | 833 |
| `PING` | 656 |
| `canary_env` | 600 |


_Generated from first-party honeypot capture. CC BY 4.0._
