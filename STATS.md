# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5628 attackers** · **1,208,546 hostile actions** · covering 67 day(s) through 2026-11-18

| signal | count |
|---|---|
| GPU / AI-hardware probing | 310 |
| Used a planted canary credential | 230 |
| Seen on more than one sensor | 470 |
| Stage-2 hosts named in payloads | 63 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11355 |
| `ssh-bruteforce` | 1793 |
| `ssh-exploit` | 1432 |
| `redis-exploit` | 1009 |
| `mcp-abuse` | 316 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 172 |
| `ollama-abuse` | 152 |
| `llamacpp-abuse` | 131 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3372 |
| `redis` | 1041 |
| `mcp` | 545 |
| `llamacpp` | 446 |
| `vllm` | 342 |
| `litellm` | 339 |
| `docker` | 305 |
| `jupyter` | 282 |
| `ollama` | 273 |
| `hfhub` | 226 |
| `php` | 161 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1835 |
| `345gs5662d34` | 1102 |
| `admin` | 905 |
| `ubuntu` | 424 |
| `guest` | 221 |
| `ftpuser` | 218 |
| `user` | 216 |
| `test` | 174 |
| `ftp` | 132 |
| `git` | 123 |
| `deploy` | 119 |
| `postgres` | 112 |
| `config` | 111 |
| `support` | 111 |
| `administrator` | 108 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1100 |
| `3245gs5662d34` | 1092 |
| `123456` | 993 |
| `123` | 612 |
| `1234` | 483 |
| `12345678` | 389 |
| `admin` | 382 |
| `12345` | 314 |
| `1` | 280 |
| `P@ssw0rd` | 238 |
| `admin123` | 236 |
| `password` | 174 |
| `123456789` | 144 |
| `000000` | 138 |
| `1111` | 131 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1548 |
| `cat` | 1332 |
| `cd` | 1326 |
| `echo` | 1306 |
| `crontab` | 1272 |
| `lscpu` | 1268 |
| `ls` | 1159 |
| `whoami` | 1154 |
| `free` | 1153 |
| `df` | 1151 |
| `top` | 1149 |
| `w` | 1149 |
| `INFO` | 715 |
| `PING` | 547 |
| `canary_env` | 444 |


_Generated from first-party honeypot capture. CC BY 4.0._
