# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**5614 attackers** · **1,208,098 hostile actions** · covering 66 day(s) through 2026-11-17

| signal | count |
|---|---|
| GPU / AI-hardware probing | 310 |
| Used a planted canary credential | 230 |
| Seen on more than one sensor | 470 |
| Stage-2 hosts named in payloads | 62 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 11318 |
| `ssh-bruteforce` | 1782 |
| `ssh-exploit` | 1433 |
| `redis-exploit` | 1008 |
| `mcp-abuse` | 316 |
| `litellm-key-replay` | 179 |
| `docker-abuse` | 172 |
| `ollama-abuse` | 150 |
| `llamacpp-abuse` | 131 |
| `jupyter-abuse` | 51 |
| `vllm-abuse` | 26 |
| `php-abuse` | 24 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3362 |
| `redis` | 1040 |
| `mcp` | 545 |
| `llamacpp` | 446 |
| `vllm` | 342 |
| `litellm` | 339 |
| `docker` | 305 |
| `jupyter` | 282 |
| `ollama` | 271 |
| `hfhub` | 226 |
| `php` | 161 |
| `ray` | 50 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1833 |
| `345gs5662d34` | 1101 |
| `admin` | 905 |
| `ubuntu` | 423 |
| `guest` | 221 |
| `ftpuser` | 218 |
| `user` | 216 |
| `test` | 175 |
| `ftp` | 132 |
| `git` | 123 |
| `deploy` | 119 |
| `postgres` | 112 |
| `support` | 112 |
| `config` | 111 |
| `administrator` | 108 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1099 |
| `3245gs5662d34` | 1092 |
| `123456` | 992 |
| `123` | 612 |
| `1234` | 482 |
| `12345678` | 389 |
| `admin` | 381 |
| `12345` | 313 |
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
| `INFO` | 714 |
| `PING` | 547 |
| `canary_env` | 444 |


_Generated from first-party honeypot capture. CC BY 4.0._
