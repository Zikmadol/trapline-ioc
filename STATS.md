# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6158 attackers** · **1,346,314 hostile actions** · covering 74 day(s) through 2026-11-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 340 |
| Used a planted canary credential | 263 |
| Seen on more than one sensor | 509 |
| Stage-2 hosts named in payloads | 73 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13557 |
| `ssh-bruteforce` | 1926 |
| `ssh-exploit` | 1464 |
| `redis-exploit` | 1116 |
| `mcp-abuse` | 348 |
| `docker-abuse` | 220 |
| `litellm-key-replay` | 197 |
| `llamacpp-abuse` | 181 |
| `ollama-abuse` | 168 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 42 |
| `vllm-abuse` | 31 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3552 |
| `redis` | 1148 |
| `mcp` | 654 |
| `llamacpp` | 575 |
| `vllm` | 443 |
| `litellm` | 414 |
| `docker` | 369 |
| `jupyter` | 322 |
| `ollama` | 299 |
| `hfhub` | 260 |
| `php` | 194 |
| `ray` | 68 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1918 |
| `345gs5662d34` | 1106 |
| `admin` | 951 |
| `ubuntu` | 438 |
| `guest` | 238 |
| `ftpuser` | 231 |
| `user` | 220 |
| `test` | 174 |
| `ftp` | 146 |
| `config` | 131 |
| `deploy` | 129 |
| `git` | 125 |
| `administrator` | 116 |
| `bin` | 115 |
| `support` | 114 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1038 |
| `123` | 633 |
| `1234` | 522 |
| `admin` | 416 |
| `12345678` | 409 |
| `12345` | 352 |
| `1` | 302 |
| `admin123` | 259 |
| `P@ssw0rd` | 253 |
| `password` | 174 |
| `123456789` | 152 |
| `1111` | 150 |
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
| `INFO` | 786 |
| `PING` | 613 |
| `canary_env` | 548 |


_Generated from first-party honeypot capture. CC BY 4.0._
