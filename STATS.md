# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6086 attackers** · **1,332,340 hostile actions** · covering 73 day(s) through 2026-11-24

| signal | count |
|---|---|
| GPU / AI-hardware probing | 334 |
| Used a planted canary credential | 261 |
| Seen on more than one sensor | 506 |
| Stage-2 hosts named in payloads | 71 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13551 |
| `ssh-bruteforce` | 1919 |
| `ssh-exploit` | 1464 |
| `redis-exploit` | 1101 |
| `mcp-abuse` | 344 |
| `docker-abuse` | 216 |
| `litellm-key-replay` | 191 |
| `ollama-abuse` | 167 |
| `llamacpp-abuse` | 157 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 42 |
| `vllm-abuse` | 29 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3542 |
| `redis` | 1133 |
| `mcp` | 624 |
| `llamacpp` | 546 |
| `vllm` | 416 |
| `litellm` | 402 |
| `docker` | 363 |
| `jupyter` | 319 |
| `ollama` | 298 |
| `hfhub` | 258 |
| `php` | 190 |
| `ray` | 62 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1914 |
| `345gs5662d34` | 1106 |
| `admin` | 946 |
| `ubuntu` | 438 |
| `guest` | 237 |
| `ftpuser` | 230 |
| `user` | 219 |
| `test` | 174 |
| `ftp` | 145 |
| `config` | 130 |
| `deploy` | 129 |
| `git` | 125 |
| `administrator` | 116 |
| `support` | 114 |
| `bin` | 114 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1035 |
| `123` | 633 |
| `1234` | 519 |
| `admin` | 409 |
| `12345678` | 408 |
| `12345` | 351 |
| `1` | 301 |
| `admin123` | 257 |
| `P@ssw0rd` | 253 |
| `password` | 172 |
| `123456789` | 152 |
| `1111` | 149 |
| `000000` | 145 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1599 |
| `cat` | 1372 |
| `cd` | 1367 |
| `echo` | 1339 |
| `crontab` | 1306 |
| `lscpu` | 1299 |
| `ls` | 1189 |
| `free` | 1183 |
| `whoami` | 1183 |
| `df` | 1180 |
| `top` | 1179 |
| `w` | 1179 |
| `INFO` | 777 |
| `PING` | 603 |
| `canary_env` | 519 |


_Generated from first-party honeypot capture. CC BY 4.0._
