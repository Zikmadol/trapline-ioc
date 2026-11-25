# What the attackers did — recent activity

Aggregate, sanitised view of **recent** activity against the Trapline honeypot sensors (the capture window below) — no raw logs, no credentials of ours, no prompts. The IP feed itself (`ips.txt`) is cumulative; these counts are the rolling window.

**6182 attackers** · **1,346,983 hostile actions** · covering 74 day(s) through 2026-11-25

| signal | count |
|---|---|
| GPU / AI-hardware probing | 340 |
| Used a planted canary credential | 263 |
| Seen on more than one sensor | 510 |
| Stage-2 hosts named in payloads | 73 |

### By category

| category | IPs |
|---|---|
| `canary-aws-key` | 13557 |
| `ssh-bruteforce` | 1928 |
| `ssh-exploit` | 1464 |
| `redis-exploit` | 1118 |
| `mcp-abuse` | 349 |
| `docker-abuse` | 221 |
| `litellm-key-replay` | 200 |
| `llamacpp-abuse` | 197 |
| `ollama-abuse` | 168 |
| `jupyter-abuse` | 55 |
| `litellm-abuse` | 41 |
| `vllm-abuse` | 31 |

### By protocol

| protocol | events |
|---|---|
| `ssh` | 3555 |
| `redis` | 1150 |
| `mcp` | 670 |
| `llamacpp` | 590 |
| `vllm` | 459 |
| `litellm` | 417 |
| `docker` | 370 |
| `jupyter` | 322 |
| `ollama` | 299 |
| `hfhub` | 261 |
| `php` | 195 |
| `ray` | 68 |

### Top usernames tried

| username | tries |
|---|---|
| `root` | 1919 |
| `345gs5662d34` | 1106 |
| `admin` | 952 |
| `ubuntu` | 438 |
| `guest` | 239 |
| `ftpuser` | 232 |
| `user` | 220 |
| `test` | 174 |
| `ftp` | 147 |
| `config` | 132 |
| `deploy` | 129 |
| `git` | 125 |
| `administrator` | 116 |
| `bin` | 116 |
| `support` | 114 |

### Top passwords tried

| password | tries |
|---|---|
| `345gs5662d34` | 1103 |
| `3245gs5662d34` | 1095 |
| `123456` | 1040 |
| `123` | 633 |
| `1234` | 523 |
| `admin` | 417 |
| `12345678` | 410 |
| `12345` | 353 |
| `1` | 302 |
| `admin123` | 260 |
| `P@ssw0rd` | 254 |
| `password` | 174 |
| `123456789` | 152 |
| `1111` | 152 |
| `000000` | 145 |

### Top commands run

| command | times |
|---|---|
| `uname` | 1600 |
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
| `INFO` | 788 |
| `PING` | 614 |
| `canary_env` | 564 |


_Generated from first-party honeypot capture. CC BY 4.0._
